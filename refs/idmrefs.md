# Digital Identity References

Sources, articles or training to increase our digital identity knowledge. I've read all articles or taken the training and recommend it to others. Recommendation is not an endorsement of a product but more "oh, here's an article on the thing we talked about". All links are external links and ordered with latest find on top. I use this as both a way to share information and also a way to keep track of good content.

## In the Queue
- [ABAC on AWS Tutorial By: AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_attribute-based-access-control.html){:target="_blank"}{:rel="noopener noreferrer"} ***Want to try this out and see if you can do the same with tags on Azure.***
- [Chesney on Cybersecurity Law, Policy, and Institutions v3.0 - March 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3547103){:target="_blank"}{:rel="noopener noreferrer"} ***Comprehensive eCasebook on the interwined nature of the legal and policy questions associated with cybersecurity.***
- [BloodHound: Six Degrees of Domain Admin Now in Azure](https://bloodhound.readthedocs.io/en/latest/index.html#bloodhound-six-degrees-of-domain-admin){:target="_blank"}{:rel="noopener noreferrer"} ***This is a cool tool to identify privilege attack paths in Active Directory and now in Azure too.***

## Webinars and Videos
- [Modern Phishing vs Common Phone and OTP Authentication via Yubico (9 min watch](https://www.youtube.com/watch?v=Ubpsledn4Tg){:target="_blank"}{:rel="noopener noreferrer"} ***Quick demonstration of how OTP and Push Notification authentications are not phishing-resistant.***
- [How to architect an identity management strategy in AWS via SANS Institute (1 hour watch)](https://pages.awscloud.com/awsmp-h2-sec-digital-workspace-iam-ty.html){:target="_blank"}{:rel="noopener noreferrer"} ***Great one hour webinar on best identity practices from AWS Well-Architected Framework with #Okta and #0Auth examples at the end.***

## Articles
- [The Beer Drinker’s Guide to SAML By: Greg Seader via Duo Blog (15 min read)](https://duo.com/blog/the-beer-drinkers-guide-to-saml){:target="_blank"}{:rel="noopener noreferrer"} ***Easier to read and understand than the SAML standard.***
- [You Need Multiple SAML IDP Signing Keys By: Hans via Hansblog (10 min read)](https://www.stackallocated.com/blog/2020/saml-idp-no-shared-keys/){:target="_blank"}{:rel="noopener noreferrer"} ***Great article on the risk in SAML signing keys and also contains a market analysis.***
- [Implementing Zero Trust with Microsoft Azure: Identity and Access Management (1 of 6) By: TJ Banasik via Azure Gov Blog (15 min read)](https://devblogs.microsoft.com/azuregov/implementing-zero-trust-with-microsoft-azure-identity-and-access-management-1-of-6/){:target="_blank"}{:rel="noopener noreferrer"}
- [Microsoft Windows Certificate Path Validation in Bridge CA and Cross-Certification Environments By Siddarth Adukia via Microsoft Tech Community (zzz read)](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/certificate-path-validation-in-bridge-ca-and-cross-certification/ba-p/1128610){:target="_blank"}{:rel="noopener noreferrer"} ***PKI path building an validation is always tricky depending on the library. CAPI2 uses a unique logic.***
- [The Line of Death by Eric Law](https://textslashplain.com/2017/01/14/the-line-of-death/){:target="_blank"}{:rel="noopener noreferrer"} - When building applications that display untrusted content, security designers have a major problem— if an attacker has full control of a block of pixels, he can make those pixels look like anything he wants, including the UI of the application itself. He can then induce the user to undertake an unsafe action, and a user will be none the wiser. In web browsers (and beyond sometimes), the browser itself usually controls the top of the window, while pixels under the top are under control of the site. I’ve recently heard this called the line of death.
- [Revocation is broken by Scott Helme via Scott Helme Blog (14 min read)](https://scotthelme.co.uk/revocation-is-broken/){:target="_blank"}{:rel="noopener noreferrer"} - We have a little problem on the web right now and I can only see this becoming a larger concern as time goes by. More and more sites are obtaining certificates, vitally important documents that we need to deploy HTTPS, but we have no way of protecting ourselves when things go wrong.

### Articles on Digital Identity Basics
- [What is Digital Identity via Liminal (10 min read)](https://liminal.co/what-is-digital-identity/){:target="_blank"}{:rel="noopener noreferrer"} **Digital identity is a facet of all our lives now, but confusion exists as to how extensive our digital identities are, and how to go about managing them.
- [Introduction to Self-Soverign Identity By: Juin Chiu via Medium (11 min read)](https://medium.com/unitychain/intro-to-ssi-7cdac15251a7){:target="_blank"}{:rel="noopener noreferrer"} ***Interesting concepts.***

### Articles on Decentralized Identity and Verifiable Credentials
- [Governance in the new age of Decentralized Identity By: Travis Jarae, Cameron D’Ambrosi, Will Charnley via Liminal Insights (10 min read)](https://liminal.co/articles/governance-in-the-new-age-of-decentralized-identity/){:target="_blank"}{:rel="noopener noreferrer"} **Nice plain language description of decentralized identity.
- [The Keys to Decentralized Identity by: Okta (32 min watch)](https://www.youtube.com/watch?v=gWfAIYXcyH4){:target="_blank"}{:rel="noopener noreferrer"} **Nice video explaination of decentralized identity.
- [Verifiable Credentials Using Blockchain By Microsoft via Youtube (15 min watch)](https://www.youtube.com/watch?v=r20hCF9NbTo){:target="_blank"}{:rel="noopener noreferrer"} **More in-depth overview of Verifiable Credentials from Microsoft.

### Articles Related to Authenticators or MFA
- [All Your Creds Belong to us By: Alex Weinert via Microsoft AAD Identity Blog (10 min read)](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/all-your-creds-are-belong-to-us/ba-p/855124){:target="_blank"}{:rel="noopener noreferrer"} ***Plainer language version of NIST 800-63-3B.***
- [What Is SMS Authentication and Is It Secure? By: Teju Shyamsundar via Okta Blogf\ (7 min read)](https://www.okta.com/blog/2020/10/sms-authentication/){:target="_blank"}{:rel="noopener noreferrer"} ***Nice synopsis of the proc/cons of SMS-based authentication. NIST did discourage it's use but walked it back.***
- [Multi-Factor Authentication Vulnerabilities By: Hashar Mujahid via InfoSec Write-ups @ Medium (4 min read)](https://infosecwriteups.com/multi-factor-authentication-vulnerabilities-7a4b647a7b09){:target="_blank"}{:rel="noopener noreferrer"} *** Two practical examples with screenshots of MFA bypass techniques due to weak login coding.***

### Articles Related to Achieving NIST 800-63-3 Levels
- [NIST Special Publication 800-63 Revision 3 Digital Identity Guidelines By: NIST (3.5 hour read)](https://pages.nist.gov/800-63-3/sp800-63-3.html){:target="_blank"}{:rel="noopener noreferrer"} ***The digital identity bible for federal government agencies. A major upgrade to 800-63-2 evolving to three separate identity, authenticator, and federation levels.***
- [NIST SPECIAL PUBLICATION 800-63-3 IMPLEMENTATION RESOURCES By: NIST (2 hour read)](https://www.nist.gov/system/files/documents/2020/07/02/SP-800-63-3-Implementation-Resources_07012020.pdf){:target="_blank"}{:rel="noopener noreferrer"} ***Accompanying guide to 800-63-3 on implementing the normative requirements of 800-63-3.***
- [ForgeRock and NIST Special Publication 800-63-3 By: ForgeRock (25 min read)](https://www.forgerock.com/resources/whitepaper/forgerock-nist-sp-800-63-3){:target="_blank"}{:rel="noopener noreferrer"} **Includes how to achieve the infamous FAL3 using SAML, OAuth 2.0, or OIDC.**
- [Achieving National Institute of Standards and Technology Authenticator Assurance Levels with the Microsoft Identity Platform By: Microsoft (25 min Read)](https://azure.microsoft.com/mediahandler/files/resourcefiles/microsoft-nist/Achieving%20NIST%20Authentication%20Assurance%20Levels%20with%20the%20Microsoft%20Identity%20Platform.pdf){:target="_blank"}{:rel="noopener noreferrer"} **How to achieve NIST 800-63-3 levels using Azure AD.**
- [Selecting Secure Multi-factor Authentication Solutions By: NSA (25 min read)](https://media.defense.gov/2020/Sep/22/2002502665/-1/-1/0/CSI_MULTIFACTOR_AUTHENTICATION_SOLUTIONS_UOO17091520.PDF){:target="_blank"}{:rel="noopener noreferrer"} ***Good overview on authenticators and how some modern solutions stack up to NIST 800-63-3B requirements.***

### Articles Related to Privilege Escalation
- [Attacking Azure, Azure AD, and Introducing PowerZure By: Ryan Hausknecht via SpectorOps (14 min read)](https://posts.specterops.io/attacking-azure-azure-ad-and-introducing-powerzure-ca70b330511a){:target="_blank"}{:rel="noopener noreferrer"}
- [Azure AD Connect for Red Teamers By: Adam Chest via XPNSec (10 min read)](https://blog.xpnsec.com/azuread-connect-for-redteam/){:target="_blank"}{:rel="noopener noreferrer"}
- [Azure Privilege Escalation via Service Principal Abuse via SpectorOps (10 min read)](https://posts.specterops.io/azure-privilege-escalation-via-service-principal-abuse-210ae2be2a5){:target="_blank"}{:rel="noopener noreferrer"} - Explains how privilege escalation can work in Azure.
- [Certifried: Active Directory Domain Privilege Escalation (13 min read) by: Oliver Lyak](https://research.ifcr.dk/certifried-active-directory-domain-privilege-escalation-cve-2022-26923-9e098fe298f4){:target="_blank"}{:rel="noopener noreferrer"} - The vulnerability allowed a low-privileged user to escalate privileges to domain administrator in a default Active Directory environment with the Active Directory Certificate Services (AD CS) server role installed. At Institute For Cyber Risk, we see AD CS environments on almost every engagement. It’s rare that we see large and medium-sized Active Directory environments without AD CS installed. The vulnerability was patched as part of the May 2022 Security Updates from Microsoft.
- [Kerberosity Killed the Domain: An Offensive Kerberos Overview (13 min read) by: Ryan Hausknecht via SpecterOps Blog](https://posts.specterops.io/kerberosity-killed-the-domain-an-offensive-kerberos-overview-eb04b1402c61){:target="_blank"}{:rel="noopener noreferrer"} - Anything great article from SpecterOps. This one on Kerberos function and vulnerabilities.
- [Monitoring Active Directory for Signs of Compromise via Microsoft Learn (24 minutes to read](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/monitoring-active-directory-for-signs-of-compromise){:target="_blank"}{:rel="noopener noreferrer"} - ***A solid event log monitoring system is a crucial part of any secure Active Directory design. Many computer security compromises could be discovered early in the event if the victims enacted appropriate event log monitoring and alerting. Independent reports have long supported this conclusion.***

### Articles Related to Federation Attacks and Golden SAML
- [Alert (AA21-008A) - Detecting Post-Compromise Threat Activity in Microsoft Cloud Environments By: DHS CISA (20 min read)](https://us-cert.cisa.gov/ncas/alerts/aa21-008a){:target="_blank"}{:rel="noopener noreferrer"} ***Excellent write-up and tools to identify compromised Microsoft federation systems.***
- [Detecting Abuse of Authentication Mechanisms By: National Security Agency](https://media.defense.gov/2020/Dec/17/2002554125/-1/-1/0/AUTHENTICATION_MECHANISMS_CSA_U_OO_198854_20.PDF){:target="_blank"}{:rel="noopener noreferrer"} ***Government resource specific to AD FS and Azure.***
  - [Best practices for securing Active Directory Federation Services By: Microsoft](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/deployment/best-practices-securing-ad-fs){:target="_blank"}{:rel="noopener noreferrer"}  ***Straight from the source.***
- [SAML Certificate Security: The Latest Findings and Potential Impacts By: Marc Rogers via Okta Security Blog (10 min read)](https://sec.okta.com/articles/2020/12/saml-certificate-security-latest-findings-and-potential-impacts){:target="_blank"}{:rel="noopener noreferrer"} ***Okta response to SAML signing key compromise and best practices.***
- [Detection and Hunting of Golden SAML Attack By: Sygnia (10 min read)](https://www.sygnia.co/golden-saml-advisory){:target="_blank"}{:rel="noopener noreferrer"} ***Another great write-up on Golden SAML attacks and mitigation.***
- [Golden SAML: Newly Discovered Attack Technique Forges Authentication to Cloud Apps By: CyberArk (15 min read)](https://www.cyberark.com/resources/threat-research-blog/golden-saml-newly-discovered-attack-technique-forges-authentication-to-cloud-apps){:target="_blank"}{:rel="noopener noreferrer"} ***Similar to Golden ticket attacks but specific to SAML key compromises.***
  - [Golden SAML Revisited: The Solorigate Connection By: Shaked Reiner via CyberArk Blog](https://www.cyberark.com/resources/threat-research-blog/golden-saml-revisited-the-solorigate-connection){:target="_blank"}{:rel="noopener noreferrer"} ***Follow-up post.***

## Tools
Coming Soon!

## Frameworks and Standards
- [The Public Sector Profile of the Pan-Canadian Trust Framework (PCTF-CCP) By: Government of Canada (2 hour read)](https://canada-ca.github.io/PCTF-CCP/){:target="_blank"}{:rel="noopener noreferrer"} ***Identity frameworks are an interesting way to see how identity is used in other sectors and cultures. This one is designed to map identity and business processes in Canada. It also helps map those processes to other international frameworks such as eIDAS, FATF, and UNCITRAL.***
- [FIDO v2.0 Security Reference 27 February 2018](https://fidoalliance.org/specs/fido-v2.0-id-20180227/fido-security-ref-v2.0-id-20180227.html){:target="_blank"}{:rel="noopener noreferrer"} ***Literally, the industry standard for phishing-resistant authenticators.***

## Academic Papers
Coming soon!

## Guides
- [The Complete JSON Tutorial By: Dan Englishby (20 min read)](https://www.codewall.co.uk/the-complete-json-tutorial-quickly-learn-json/){:target="_blank"}{:rel="noopener noreferrer"} #**Great guide on how to understand and use JSON. JSON format is used by cloud-based identity vendors to either share information or write access policies.***

## Free IAM or IAM-Related Training
- [Microsoft SC-300 Learning Modules - Microsoft Identity and Access Administrator (Eight Hours)](https://docs.microsoft.com/en-us/learn/browse/?terms=sc-300){:target="_blank"}{:rel="noopener noreferrer"} ***The Microsoft Identity and Access Administrator designs, implements, and operates an organization’s identity and access management systems by using Azure Active Directory (Azure AD).  This is same course I used to pass the SC-300. I also used the MeasureUp practice test.***
- [Okta Basics Curriculum by Okta (Six hours)](https://www.okta.com/training/okta-basics-curriculum-for-workforce-identity/){:target="_blank"}{:rel="noopener noreferrer"} ***Free for customers and developers. You can get a free developer account. Solid identity basics with how to deploy them on Okta.***
- [MITRE ATT&CK for Cyber Threat Intelligence Training By MITRE (Four Hours)](https://attack.mitre.org/resources/training/cti/){:target="_blank"}{:rel="noopener noreferrer"} ***How to use MITRE ATT&CK which includes identity-based attack vectors.***
- [Introduction to Google Cloud Identity by Google on Coursera (Eight Hours)](https://www.coursera.org/learn/cloud-identity){:target="_blank"}{:rel="noopener noreferrer"} ***Free content and hands-on training with trial GCP account. Pay if you want a certificate. Good intro course on cloud identity management and specifically Google Cloud Directory, SSO, MDM, and security.***
- [Keycloak Overview (One Hour)](https://www.katacoda.com/keycloak){:target="_blank"}{:rel="noopener noreferrer"} ***Basic overview of Keycloak including realms, user management, and application integration.***

## Identity Certifications
Coming Soon! Identity-specific certifications.
