# Identity Management References

Sources, articles or training to increase our Identity and Access Management knowledge. I've read all articles or taken the training and recommend it to others. Recommendation is not an endorsement of a product but more "oh, here's an article on the thing we talked about". All links are external links and ordered with latest find on top. I use this as both a way to share information and also a way to keep track of good content.

## In the Queue
1. [ABAC on AWS Tutorial By: AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_attribute-based-access-control.html){:target="_blank"} ***Want to try this out and see if you can do the same with tags on Azure.***

### Articles
8. [The Beer Drinker’s Guide to SAML By: Greg Seader via Duo Blog (15 min read)](https://duo.com/blog/the-beer-drinkers-guide-to-saml){:target="_blank"} ***Easier to read and understand than the SAML standard.***
7. [You Need Multiple SAML IDP Signing Keys By: Hans via Hansblog (10 min read)](https://www.stackallocated.com/blog/2020/saml-idp-no-shared-keys/){:target="_blank"} ***Great article on the risk in SAML signing keys and also contains a market analysis.***
6. [Implementing Zero Trust with Microsoft Azure: Identity and Access Management (1 of 6) By: TJ Banasik via Azure Gov Blog (15 min read)](https://devblogs.microsoft.com/azuregov/implementing-zero-trust-with-microsoft-azure-identity-and-access-management-1-of-6/){:target="_blank"}
5. [Attacking Azure, Azure AD, and Introducing PowerZure By: Ryan Hausknecht via SpectorOps (14 min read)](https://posts.specterops.io/attacking-azure-azure-ad-and-introducing-powerzure-ca70b330511a){:target="_blank"}
4. [What Is SMS Authentication and Is It Secure? By: Teju Shyamsundar via Okta Blogf (7 min read)](https://www.okta.com/blog/2020/10/sms-authentication/){:target="_blank"} ***Nice synopsis of the proc/cons of SMS-based authentication. NIST did discourage it's use but walked it back.***
3. [Microsoft Windows Certificate Path Validation in Bridge CA and Cross-Certification Environments By Siddarth Adukia via Microsoft Tech Community (zzz read)](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/certificate-path-validation-in-bridge-ca-and-cross-certification/ba-p/1128610){:target="_blank"} ***PKI path building an validation is always tricky depending on the library. CAPI2 uses a unique logic.***
2. [Introduction to Self-Soverign Identity By: Juin Chiu via Medium (11 min read)](https://medium.com/unitychain/intro-to-ssi-7cdac15251a7){:target="_blank"} ***Interesting concepts.***
1. [Azure AD Connect for Red Teamers By: Adam Chest via XPNSec (10 min read)](https://blog.xpnsec.com/azuread-connect-for-redteam/){:target="_blank"}

### Articles Related to Federation Attacks and Golden SAML
4. [SAML Certificate Security: The Latest Findings and Potential Impacts By: Marc Rogers via Okta Security Blog (10 min read)](https://sec.okta.com/articles/2020/12/saml-certificate-security-latest-findings-and-potential-impacts){:target="_blank"} ***Okta response to SAML signing key compromise and best practices.***
3. [Detection and Hunting of Golden SAML Attack By: Sygnia (10 min read)](https://www.sygnia.co/golden-saml-advisory){:target="_blank"} ***Another great write-up on Golden SAML attacks and mitigation.***
2. [Alert (AA21-008A) - Detecting Post-Compromise Threat Activity in Microsoft Cloud Environments By: DHS CISA (20 min read)](https://us-cert.cisa.gov/ncas/alerts/aa21-008a){:target="_blank"} ***Excellent write-up and tools to identify compromised Microsoft federation systems.***
1. [Golden SAML: Newly Discovered Attack Technique Forges Authentication to Cloud Apps By: CyberArk (15 min read)](https://www.cyberark.com/resources/threat-research-blog/golden-saml-newly-discovered-attack-technique-forges-authentication-to-cloud-apps){:target="_blank"} ***Similar to Golden ticket attacks but specific to SAML key compromises.***

## Frameworks and Standards
2. [NIST Special Publication 800-63 Revision 3 Digital Identity Guidelines By: NIST (3.5 hour read)](https://pages.nist.gov/800-63-3/sp800-63-3.html){:target="_blank"} ***The digital identity bible for federal government agencies. A major upgrade to 800-63-3 evolving to three separate identity, authenticator, and federation levels.***
  - [NIST SPECIAL PUBLICATION 800-63-3 IMPLEMENTATION RESOURCES By: NIST (2 hour read)](https://www.nist.gov/system/files/documents/2020/07/02/SP-800-63-3-Implementation-Resources_07012020.pdf){:target="_blank"} ***Accompanying guide to 800-63-3 on implementing the normative requirements of 800-63-3.***
1. [The Public Sector Profile of the Pan-Canadian Trust Framework (PCTF-CCP) By: Government of Canada (2 hour read)](https://canada-ca.github.io/PCTF-CCP/){:target="_blank"} ***Identity frameworks are an interesting way to see how identity is used in other sectors and cultures. This one is designed to map identity and business processes in Canada. It also helps map those processes to other international frameworks such as eIDAS, FATF, and UNCITRAL.***

## Guides
2. [Selecting Secure Multi-factor Authentication Solutions By: NSA (25 min read)](https://media.defense.gov/2020/Sep/22/2002502665/-1/-1/0/CSI_MULTIFACTOR_AUTHENTICATION_SOLUTIONS_UOO17091520.PDF){:target="_blank"} ***Good overview on authenticators and how some modern solutions stack up to NIST 800-63-3B requirements.***
1. [The Complete JSON Tutorial By: Dan Englishby (20 min read)](https://www.codewall.co.uk/the-complete-json-tutorial-quickly-learn-json/){:target="_blank"} #**Great guide on how to understand and use JSON. JSON format is used by cloud-based identity vendors to either share information or write access policies.***

## Free IAM or IAM-Related Training
3. [Okta Basics Curriculum by Okta (Six hours)](https://www.okta.com/training/okta-basics-curriculum-for-workforce-identity/){:target="_blank"} ***Free for customers and developers. You can get a free developer account. Solid identity basics with how to deploy them on Okta.***
2. [MITRE ATT&CK for Cyber Threat Intelligence Training By MITRE (Four Hours)](https://attack.mitre.org/resources/training/cti/){:target="_blank"} ***How to use MITRE ATT&CK which includes identity-based attack vectors.***
1. [Introduction to Google Cloud Identity by Google on Coursera (Eight Hours)](https://www.coursera.org/learn/cloud-identity){:target="_blank"} ***Free content and hands-on training with trial GCP account. Pay if you want a certificate. Good intro course on cloud identity management and specifically Google Cloud Directory, SSO, MDM, and security.***
