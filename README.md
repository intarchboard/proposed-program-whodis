# Proposed program on Wholistic Human-Oriented Discussions on Identity Systems (WHODIS)

Identity is a fundamental concept in both computing and human interactions. It is used as the basis for security policy enforcement in support of authentication, authorization, provisioning, and related access control technologies. For example, identities are used to identify human users or devices as part of end-to-end encryption applications, or used to authenticate entities that publish signed software artifacts. Identities may also be used for provisioning or managing devices or workloads in machine-to-machine systems.

The identity ecosystems that support these use cases are individually and collectively vast, including classical forms of identities such as email addresses, phone numbers, and certificates, to new forms of identities built on standards such as [OAuth [1]](https://datatracker.ietf.org/doc/html/rfc6749) and [Verifiable Credentials [2]](https://www.w3.org/TR/vc-data-model/). These different identities vary in type (what sort of entity does the identity refer to?), uniqueness (does it refer to one or more entities?), security (how easy is it for identities to be spoofed?), longevity (is the identifier for some identity still valid at this moment?), and so on.

This program has several high-level goals. First, the program will survey and collate a non-exhaustive list of identity mechansisms standardized or otherwise impacted by standards developed within the IETF. Second, the program will examine existing uses of these identity mechanisms within the Internet, seeking to understand how identities are used or misused to solve real world problems. Third, the program will discuss what use cases are currently uncovered or otherwise inadequately addressed, with the intent of identifying gaps and opportunities for technical solutions to known problems that could be developed within the IETF.

In working towards these goals, the program could collect important use cases addressed by existing identity mechanisms developed or influenced by IETF standards, discuss functional requirements (e.g., trust model, access control, support for roles, etc.) essential for these use cases, and showcase how existing identity mechanisms meet or exceed these requirements. Examining technologies built on IETF standards, such as [FedCM [3]](https://developer.chrome.com/en/docs/privacy-sandbox/fedcm/) and OAuth-based federated login systems, might influence these discovery tasks. The program could also look at ways in which identities are misused or misappropriated for solving problems for which there are better solutions. As an example, using client IP addresses as a form of identity may once have been a reasonable way to implement server-side security controls, but these lack uniqueness and reliability properties that are essential for meaningful security controls.

Possible outputs from the program include:
- Document the current state of the identity ecosystem rooted in standardization work of the IETF, including different applications and types of identities used in practice, as well as notable gaps where opportunities for additional technical work on identity mechanisms exist in the IETF or other venues.
- Coordinate one or more IAB workshops on identity-related topics to drive engagement across groups within the IETF, as well as encourage participation from contributors outside of the IETF.
- Identify opportunities for relationships with other organizations working on identity technologies (e.g., OASIS, TCG, FIDO, OIDF, REFEDS).
- Identify potential new or existing venues within the IETF and/or IRTF to progress work in this space.

References:
- [1] https://datatracker.ietf.org/doc/html/rfc6749
- [2] https://www.w3.org/TR/vc-data-model/
- [3] https://developer.chrome.com/en/docs/privacy-sandbox/fedcm/
