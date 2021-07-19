# Identity and Access Management References

Sources, articles or training to increase our Identity and Access Management knowledge. I've read all articles or taken the training and recommend it to others. Recommendation is not an endorsement of a product but more "oh, here's an article on the thing we talked about". All links are external links and ordered with latest find on top. I use this as both a way to share information and also a way to keep track of good content.

## In the Queue
- [ABAC on AWS Tutorial By: AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_attribute-based-access-control.html){:target="_blank"}{:rel="noopener noreferrer"} ***Want to try this out and see if you can do the same with tags on Azure.***
- [Chesney on Cybersecurity Law, Policy, and Institutions v3.0 - March 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3547103){:target="_blank"}{:rel="noopener noreferrer"} ***Comprehensive eCasebook on the interwined nature of the legal and policy questions associated with cybersecurity.***

## Webinars and Videos
- [How to architect an identity management strategy in AWS via SANS Institute (1 hour watch)](https://pages.awscloud.com/awsmp-h2-sec-digital-workspace-iam-ty.html){:target="_blank"}{:rel="noopener noreferrer"} ***Great one hour webinar on best identity practices from AWS Well-Architected Framework with #Okta and #0Auth examples at the end.***

## Articles
- [The Beer Drinker’s Guide to SAML By: Greg Seader via Duo Blog (15 min read)](https://duo.com/blog/the-beer-drinkers-guide-to-saml){:target="_blank"}{:rel="noopener noreferrer"} ***Easier to read and understand than the SAML standard.***
- [You Need Multiple SAML IDP Signing Keys By: Hans via Hansblog (10 min read)](https://www.stackallocated.com/blog/2020/saml-idp-no-shared-keys/){:target="_blank"}{:rel="noopener noreferrer"} ***Great article on the risk in SAML signing keys and also contains a market analysis.***
- [Implementing Zero Trust with Microsoft Azure: Identity and Access Management (1 of 6) By: TJ Banasik via Azure Gov Blog (15 min read)](https://devblogs.microsoft.com/azuregov/implementing-zero-trust-with-microsoft-azure-identity-and-access-management-1-of-6/){:target="_blank"}{:rel="noopener noreferrer"}
- [Attacking Azure, Azure AD, and Introducing PowerZure By: Ryan Hausknecht via SpectorOps (14 min read)](https://posts.specterops.io/attacking-azure-azure-ad-and-introducing-powerzure-ca70b330511a){:target="_blank"}{:rel="noopener noreferrer"}
- [What Is SMS Authentication and Is It Secure? By: Teju Shyamsundar via Okta Blogf (7 min read)](https://www.okta.com/blog/2020/10/sms-authentication/){:target="_blank"}{:rel="noopener noreferrer"} ***Nice synopsis of the proc/cons of SMS-based authentication. NIST did discourage it's use but walked it back.***
- [Microsoft Windows Certificate Path Validation in Bridge CA and Cross-Certification Environments By Siddarth Adukia via Microsoft Tech Community (zzz read)](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/certificate-path-validation-in-bridge-ca-and-cross-certification/ba-p/1128610){:target="_blank"}{:rel="noopener noreferrer"} ***PKI path building an validation is always tricky depending on the library. CAPI2 uses a unique logic.***
- [Introduction to Self-Soverign Identity By: Juin Chiu via Medium (11 min read)](https://medium.com/unitychain/intro-to-ssi-7cdac15251a7){:target="_blank"}{:rel="noopener noreferrer"} ***Interesting concepts.***
- [Azure AD Connect for Red Teamers By: Adam Chest via XPNSec (10 min read)](https://blog.xpnsec.com/azuread-connect-for-redteam/){:target="_blank"}{:rel="noopener noreferrer"}

### Articles Related to Federation Attacks and Golden SAML
- [Detecting Abuse of Authentication Mechanisms By: National Security Agency](https://media.defense.gov/2020/Dec/17/2002554125/-1/-1/0/AUTHENTICATION_MECHANISMS_CSA_U_OO_198854_20.PDF){:target="_blank"}{:rel="noopener noreferrer"} ***Government resource specific to AD FS and Azure.***
  - [Best practices for securing Active Directory Federation Services By: Microsoft](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/deployment/best-practices-securing-ad-fs){:target="_blank"}{:rel="noopener noreferrer"}  ***Straight from the source.***
- [SAML Certificate Security: The Latest Findings and Potential Impacts By: Marc Rogers via Okta Security Blog (10 min read)](https://sec.okta.com/articles/2020/12/saml-certificate-security-latest-findings-and-potential-impacts){:target="_blank"}{:rel="noopener noreferrer"} ***Okta response to SAML signing key compromise and best practices.***
- [Detection and Hunting of Golden SAML Attack By: Sygnia (10 min read)](https://www.sygnia.co/golden-saml-advisory){:target="_blank"}{:rel="noopener noreferrer"} ***Another great write-up on Golden SAML attacks and mitigation.***
- [Alert (AA21-008A) - Detecting Post-Compromise Threat Activity in Microsoft Cloud Environments By: DHS CISA (20 min read)](https://us-cert.cisa.gov/ncas/alerts/aa21-008a){:target="_blank"}{:rel="noopener noreferrer"} ***Excellent write-up and tools to identify compromised Microsoft federation systems.***
- [Golden SAML: Newly Discovered Attack Technique Forges Authentication to Cloud Apps By: CyberArk (15 min read)](https://www.cyberark.com/resources/threat-research-blog/golden-saml-newly-discovered-attack-technique-forges-authentication-to-cloud-apps){:target="_blank"}{:rel="noopener noreferrer"} ***Similar to Golden ticket attacks but specific to SAML key compromises.***
  - [Golden SAML Revisited: The Solorigate Connection By: Shaked Reiner via CyberArk Blog](https://www.cyberark.com/resources/threat-research-blog/golden-saml-revisited-the-solorigate-connection){:target="_blank"}{:rel="noopener noreferrer"} ***Follow-up post.***

## Frameworks and Standards
- [NIST Special Publication 800-63 Revision 3 Digital Identity Guidelines By: NIST (3.5 hour read)](https://pages.nist.gov/800-63-3/sp800-63-3.html){:target="_blank"}{:rel="noopener noreferrer"} ***The digital identity bible for federal government agencies. A major upgrade to 800-63-2 evolving to three separate identity, authenticator, and federation levels.***
  - [NIST SPECIAL PUBLICATION 800-63-3 IMPLEMENTATION RESOURCES By: NIST (2 hour read)](https://www.nist.gov/system/files/documents/2020/07/02/SP-800-63-3-Implementation-Resources_07012020.pdf){:target="_blank"}{:rel="noopener noreferrer"} ***Accompanying guide to 800-63-3 on implementing the normative requirements of 800-63-3.***
- [The Public Sector Profile of the Pan-Canadian Trust Framework (PCTF-CCP) By: Government of Canada (2 hour read)](https://canada-ca.github.io/PCTF-CCP/){:target="_blank"}{:rel="noopener noreferrer"} ***Identity frameworks are an interesting way to see how identity is used in other sectors and cultures. This one is designed to map identity and business processes in Canada. It also helps map those processes to other international frameworks such as eIDAS, FATF, and UNCITRAL.***

## Academic Papers
Coming soon!

## Guides
- [Achieving National Institute of Standards and Technology Authenticator Assurance Levels with the Microsoft Identity Platform By: Microsoft (25 min Read)](https://azure.microsoft.com/mediahandler/files/resourcefiles/microsoft-nist/Achieving%20NIST%20Authentication%20Assurance%20Levels%20with%20the%20Microsoft%20Identity%20Platform.pdf)**How to achieve NIST 800-63-3 levels using Azure AD.**
- [Selecting Secure Multi-factor Authentication Solutions By: NSA (25 min read)](https://media.defense.gov/2020/Sep/22/2002502665/-1/-1/0/CSI_MULTIFACTOR_AUTHENTICATION_SOLUTIONS_UOO17091520.PDF){:target="_blank"}{:rel="noopener noreferrer"} ***Good overview on authenticators and how some modern solutions stack up to NIST 800-63-3B requirements.***
- [The Complete JSON Tutorial By: Dan Englishby (20 min read)](https://www.codewall.co.uk/the-complete-json-tutorial-quickly-learn-json/){:target="_blank"}{:rel="noopener noreferrer"} #**Great guide on how to understand and use JSON. JSON format is used by cloud-based identity vendors to either share information or write access policies.***

## Free IAM or IAM-Related Training
- [Okta Basics Curriculum by Okta (Six hours)](https://www.okta.com/training/okta-basics-curriculum-for-workforce-identity/){:target="_blank"}{:rel="noopener noreferrer"} ***Free for customers and developers. You can get a free developer account. Solid identity basics with how to deploy them on Okta.***
- [MITRE ATT&CK for Cyber Threat Intelligence Training By MITRE (Four Hours)](https://attack.mitre.org/resources/training/cti/){:target="_blank"}{:rel="noopener noreferrer"} ***How to use MITRE ATT&CK which includes identity-based attack vectors.***
- [Introduction to Google Cloud Identity by Google on Coursera (Eight Hours)](https://www.coursera.org/learn/cloud-identity){:target="_blank"}{:rel="noopener noreferrer"} ***Free content and hands-on training with trial GCP account. Pay if you want a certificate. Good intro course on cloud identity management and specifically Google Cloud Directory, SSO, MDM, and security.***
