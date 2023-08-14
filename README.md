# Proposed program on Wholistic Human-Oriented Discussions on Identity Systems (WHODIS)

Identity is a fundamental concept in both computing and human interactions. It is used as the basis for security policy enforcement in support of authentication, authorization, provisioning, and related access control technologies. For example, identities are used to identify human users or devices as part of end-to-end encryption applications, or used to authenticate entities that publish signed software artifacts. Identitifiers may also be used for provisioning or managing devices or workloads in machine-to-machine systems.

The identity ecosystems that support these use cases are individually and collectively vast, including classical forms of identifiers that are network end points such as email addresses, phone numbers. There are also systems for issuing certificates that have some rudimentary identity information about the owner of public keys that are are used to secure connection between entities. 

The first generation of specifically self conscious identity standards emerged out of the directory wars of the 1990s and led to the develompent of [LDAP[1]](https://www.rfc-editor.org/rfc/rfc4511) and [SAML[2]](https://www.oasis-open.org/standard/saml/) and was focused on enterprise single sign on and 
The emergence of the consumer web led to the development of standards like the original OpenID, then development of Open Authorization [OAuth [3]](https://datatracker.ietf.org/doc/html/rfc6749) and then the next generation of OpenID Connect built on top of OAuth. 
Decentralized Identity paradigms emerged out of fora like the [Internet Identity Workshop [4]](https://internetidentityworkshop.com/) have led to the emergence of protocols that support a three party model to exchange information about the identity of people, organizations and things inclusing [Decentralized Identifier[5]](https://www.w3.org/TR/did-core/) [Verifiable Credentials [6]](https://www.w3.org/TR/vc-data-model/). 

These different identity and identifier systems vary in type (what sort of entity does the identifier/identity refer to?), uniqueness (does it refer to one or more entities?), security (how easy is it for identities to be spoofed?), longevity (is the identifier still valid at this moment?), and so on.

This program has several high-level goals. First, the program will survey the standardization landscape to determine what types of identity mechanisms exist and where they are being developed. Second, the program will examine the existing use of these identity mechanisms within the Internet, seeking to understand how identities are used or misused to solve real world problems. Third, the program will discuss what use cases are currently uncovered or otherwise inadequately addressed, with the intent of identifying gaps and opportunities for technical solutions to known problems that could be developed within the IETF or other venues. 

In working towards these goals, the program could collect important use cases addressed by existing identity mechanisms, discuss functional requirements (e.g., trust model, access control, support for roles, etc.) essential for these use cases, and showcase how existing identity mechanisms meet or exceed these requirements. The program could also look at ways in which identities are misused or misappropriated for solving problems for which there are better solutions. As an example, using client IP addresses as a form of identity may once have been a reasonable way to implement server-side security controls, but these lack uniqueness and reliability properties that are essential for meaningful security controls. 

Possible outputs from the program include:
- Document the current state of the identity ecosystem, including different applications and types of identities used in practice, as well as notable gaps where opportunities for additional technical work on identity mechanisms exist in the IETF or other venues.
- Coordinate one or more IAB workshops on identity-related topics to drive engagement between the IETF and other communities.
- Identify opportunities for relationships with other organizations working on identity technologies (e.g., IIW, OASIS, W3C, TCG, FIDO, OIDF, REFEDS).
- Identify potential new or existing venues within the IETF and/or IRTF to progress work in this space.

References:
- [1] https://www.rfc-editor.org/rfc/rfc4511
- [2] https://www.oasis-open.org/standard/saml/
- [3] https://datatracker.ietf.org/doc/html/rfc6749
- [4] https://internetidentityworkshop.com/
- [5] https://www.w3.org/TR/did-core/
- [6] https://www.w3.org/TR/vc-data-model/
