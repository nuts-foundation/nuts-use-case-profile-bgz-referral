# nuts-use-case-profile-bgz-referral
The document describes how to use the Nuts-specifications in the context of a medical specialist referral, commonly known as a "BgZ-referral"

# Introduction
This document describes how to use the Nuts-specifications in the context of a medical specialist referral, commonly known as a "BgZ-referral". This includes the specific agreements that, in addition to the specification '[TA-Notified-Pull-on-Nuts](https://github.com/jorritspee/TA-Notified-Pull-on-Nuts)', apply to the use case of medical specialist referrals.
This document describes:
- the identifier of the use case;
- the governance;
- the information standards;
- the permitted means of authentication;
- the permitted bases;
- name of actors; and
- the access policy.

# use case identifier
The identifier of the use case is 'bgz-referral'.

# Governance
to do
- Information standards are developed and maintained by standardization organization Nictiz

# Information standards
- The content and structure of the information to be exchanged complies with the Functional Design Information Standard BgZ: https://informatiestandaarden.nictiz.nl/wiki/BgZ:V1.0_BgZ_MSZ_Informatiestandaard
- The structure of the data to be exchanged and the data interfaces to be used complies with the Technical Design Information Standard BgZ: https://informatiestandaarden.nictiz.nl/wiki/BgZ:V1.0_BgZ_2017_Technical_IG

# Permitted means of authentication of healthcare professionals
In order to share data securely between different healthcare providers, cross-organizatonal authentication of healthcare professionals is essential. For this use case the following means of healthcare professionals are permitted:
- EmployeeID (support is mandatory): as specified in [RFC019 Employee Identity Authentication Means](https://nuts-foundation.gitbook.io/drafts/rfc/rfc019-employee-identity-means)https://nuts-foundation.gitbook.io/drafts/rfc/rfc019-employee-identity-means
- IRMA/Yivi (support is optional): as specified in [RFC002 Authentication token chapter 7.1](https://nuts-foundation.gitbook.io/drafts/rfc/rfc002-authentication-token#id-7.1.-irma)https://nuts-foundation.gitbook.io/drafts/rfc/rfc002-authentication-token#id-7.1.-irma
- UZI smartcard (support is optional): as specified in [RFC002 Authentication token chapter 7.2](https://nuts-foundation.gitbook.io/drafts/rfc/rfc002-authentication-token#id-7.2-uzi)https://nuts-foundation.gitbook.io/drafts/rfc/rfc002-authentication-token#id-7.2-uzi

# Permitted legal bases and evidence
The following legal bases are supported for the use case medical specialist referral:
- 'implicit consent'
- 'explicit prior consent': not necessary because in a referral situation consent can be implied

The following evidence is allowed for 'implicit consent':
- registration in the source system used by the referrer
- verbal consent given to the referrer

# Naming of actors
to do (maybe not necessary)

# Data availability
- Every party that offers services for the use case bgz-referral is responsible for the availability of its own infrastructure, the system and the Nuts-node.
- Data holders ensure the availability of all components that are part of TA-Notified-Pull-on-Nuts in accordance with the requirements for Availability, Integrity and -Confidentiality as included in the article <<TO DO WAAR??>>.

# Access Policy
TO DO: copy past translate chapter 6 of https://docs.google.com/document/d/1XzApaGJew3XgyWzAP30JMMi9brjGtfqLG8cIHk5zGEQ/edit?usp=sharing.


