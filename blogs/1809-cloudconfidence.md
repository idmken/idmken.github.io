Reproduced here from the [Protiviti Technology Blog](https://tcblog.protiviti.com/2018/09/06/worried-about-regulatory-compliance-with-cloud-data-use-a-casb/){:target="_blank"}{:rel="noopener noreferrer"}
September 6, 2018

# Worried About Regulatory Compliance with Cloud Data? Use a CASB

Kenneth Myers  
September 6, 2018  
5 min read  

As IT evolves to incorporate virtual and serverless interfaces, more enterprises are operating in multicloud environments. Unfortunately, corporate users operating in such environments often and unknowingly risk causing data security breaches when moving corporate data between enterprise environments when no protections and policies are in place to stop data migration or loss, as well as when accessing corporate data with personal devices. However, cloud access security brokers (CASBs) can help organizations govern access and security to cloud-based data.

CASBs accomplish this by distinguishing sanctioned applications (those procured and managed by the organization) from unsanctioned ones that many employees choose to use to carry out work tasks without the organization’s permission. In such cases, workers rationalize their use of personal accounts with Evernote, Microsoft Office 365, Google’s G Suite and other software-as-a-service applications by saying, “It’s so hard to use my corporate apps, and I like using X.” In addition, an employee may not recognize the difference between using a corporate account and a personal account when loading or moving data.

Gartner reports that by 2020, 60 percent of organizations will use CASBs to govern cloud services for the following reasons:

- Single-sign-on solutions help control user access but usually have no visibility into how many applications are using a credential (e.g., a corporate Gmail credential).
- A firewall blacklist may limit internal user access to applications, but it does not stop external user access to sanctioned applications (e.g., limit cloud application access to corporate networks).
- Security policies are defined per applications but are not applied consistently across various cloud platforms or applications.

Essentially, CASBs are built to protect data exchanges within and among cloud applications, complementing rather than replacing many existing security appliances, such as web proxies and firewalls. While the latter provide inbound threat protection and website filtering, CASBs, deployed via an application programming interface or end-point agent to fit most enterprise architecture needs, offer additional, fine-grained control in managing cloud data and cloud application use. CASBs also enable consistent access and data policies across multiple cloud providers and fine-grained control over user activity. Typical CASB use cases include:

- Monitoring and controlling end-point access to cloud platforms (e.g., Azure, AWS and Google) and applications (e.g., Salesforce, G Suite and Office 365)
- Preventing access from unregistered devices or users or to third-party applications, such as using a corporate Gmail or Office 365 credential to log in to an unsanctioned CRM application
- Controlling internal and external user access and activity on sanctioned corporate-managed applications such as limiting ability to share, create, delete, download, and/or edit
- Controlling internal user access to unsanctioned personal applications used to conduct corporate activity
- Providing a dashboard and metrics on cloud usage and user activity across both devices and access points

Some CASB solutions can be combined with a hardware-security module (HSM) for encryption, tokenization and data-loss prevention. Be aware, however, that depending on the HSM integration and control, it may lock in an organization with a specific vendor. Preventing access from unregistered devices and users folds into a broader threat-protection and user and entity behavior analytics (UEBA) capability for on-demand access decisions, threat intelligence, detection, and other forms of anomalous behavior detection and response.

Some of the top concerns from our clients with multicloud environments pertain to how to maintain regulatory compliance. With the enforcement of the European Union’s General Data Protection Regulation (GDPR) regarding breach notification and fines (up to 4 percent of annual revenue), a tool like a CASB is in greater demand. A CASB offers the following benefits:

- Identifies personal data – A CASB scans both data at rest and in transit and can identify personal identifiable information such as names, phone numbers and Social Security numbers. These scans can also help an enterprise identify records of processing activities (ROPAs), requirements in enterprise cloud applications.
- Controls data access – A CASB can help control access to and restrict use of data by, for example, creating geofences, which will also meet data residency restrictions (e.g., a geofence can stop data leaving the EU for the United States and vice versa or encrypt it to meet GDPR requirements). A CASB can also prevent use of corporate credentials on unsanctioned applications.
- Identifies abnormal behavior – A CASB gives an enterprise visibility into its multicloud environment to provide a centralized view of user behavior, which helps identify attributes of a potential breach, use of compromised credentials or other signs of a potential compromise.

Within the Protiviti IAM framework, CASBs span the what-you-can-access components of data stores and security services, access and risk management, and authorization. While CASBs aren’t meant to replace current IAM components, they can supplement implementations for greater visibility into cloud use. They essentially act more like a glue between IAM components to help enterprises ensure strong access-control and data-security policy.
