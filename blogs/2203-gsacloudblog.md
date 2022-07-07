Reproduced here from the [GSA Blog]([https://isaca-gwdc.org/2021-draft-federal-zero-trust-strategy/](https://www.gsa.gov/blog/2022/03/09/achieve-zero-trust-capabilities-using-these-cloud-identity-adoption-best-practices)){:target="_blank"}{:rel="noopener noreferrer"}

# Achieve Zero Trust Capabilities Using These Cloud Identity Adoption Best Practices

March 09, 2022 | Identity Assurance and Trusted Access Division, GSA OGP

Post filed in: [Cloud](https://www.gsa.gov/blog/blog-search?category=Cloud){:target="_blank"}{:rel="noopener noreferrer"}

Foundational to the security of both on-premises and cloud environments, an identity-based process like identity proofing or authentication is the first touchpoint to access data and impacts user experience. In cloud environments, application authentication protects data and workloads where traditionally organizations relied on network-based security because users, data, and workloads were on an agency's network. With cloud-based services, users, data, and workloads are no longer protected by network-based security. As mentioned in [OMB Memo 22-09](https://zerotrust.cyber.gov/federal-zero-trust-strategy/){:target="_blank"}{:rel="noopener noreferrer"}, zero trust is "a dramatic paradigm shift in the philosophy of how we secure our infrastructure, networks, and data, from verifying once at the perimeter to continual verification of each user, device, application, and transaction." Using cloud-based identity services can help agencies achieve zero trust goals identified in OMB Memo 22-09.

To address the differences between on-premises and cloud identity architectures, the Federal Chief Information Security Officer Council's Identity, Credential, and Access Management Subcommittee in collaboration with the Federal Chief Information Officers Council's Cloud & Infrastructure Community of Practice created a Cloud Identity Working Group.

This working group recently wrote the [Cloud Identity Playbook](https://playbooks.idmanagement.gov/playbooks/cloud/){:target="_blank"}{:rel="noopener noreferrer"}, a practical guide to help federal agencies as they begin or expand the use of workforce identity, credentialing, and access management services delivered via the cloud. The working group identified best practices for both person and non-person workforce identity. A non-person in this context is a server, network device, robotic process automation, or any other type of hardware or software-based entity in cyberspace. The most common cloud identity verification example is identity as a service (IDaaS). An IDaaS is typically an identity provider (IdP) that offers single sign-on, multifactor authentication, and directory services in a single platform.

![Flowchart of cloud single sign-on.](../../assets/gsa-cloudidentityexample.png)

## What is different between an on-premises identity provider and a cloud-based one?

In this playbook, "on-premises" is defined as an agency operating identity services on agency-owned and maintained infrastructure. Transitioning to an IDaaS 'as-a-service' model will allow federal agencies to buy capabilities rather than invest in infrastructure. The table below highlights the main differences between operating an on-premises Identity Provider and leveraging an IDaaS based on the five essential cloud characteristics of the National Institute of Science and Technology (NIST). For more information on cloud basics, see the GSA Cloud Information Center.

| Essential Characteristic	| On-Premises IdP	| IDaaS |
| ----- | ------- | ------- |
| On-Demand Self Service - Consumer can provision infrastructure.	| Complete control over all configuration settings.	| Privileges are limited to those allowed by the service.|
|Rapid Elasticity - Infrastructure scales rapidly based on demand.	| They are limited but potentially automated scaling to the number of dedicated servers.	| Unlimited and automated scaling is transparent to the user and typically included in base IDaaS pricing. |
| Measured Service - Usage is monitored, controlled, and reported to the consumer (i.e., pay for what you use).	| Pricing is usually perpetual-based software licensing or, by the number of instances.	| Based on the total number of users, active users, or applications. |
| Resource Pooling - Shared physical and logical resources dynamically assigned.	| Hardware is dedicated commercial or government-furnished equipment maintained by a federal agency.	| Hardware is shared, commercial hardware owned and maintained by a cloud service provider, logically segmented by customer.|
| Broad Network Access - Available over the internet and accessed from standard devices. |	Creating an internet-accessible service may require additional load balancers, network bandwidth, user device configuration, and geographic dispersion.	| Globally available through geographic-based content delivery networks that offer up to or exceeding 99.99% ("four nines") reliability.| 

## Where does an agency start its journey toward IDaaS

Agency program managers who handle identity, credential, and access management (ICAM) issues - as well as others - can use these four steps to plan their cloud identity verification journey:

1. Gain leadership support through collaborating on a migration path. Create user stories that encourage cloud identity services to improve user experience and business processes. Capture these in a business case. Align your business case with your agency's zero trust architecture initiative.
2. Identify your success factors and document a plan that addresses policy and strategy.
3. Understand unique cloud identity architecture considerations across identity management, credential management, access management, governance, and federation.
4. Test and deploy identity automation.

Each step includes recommended best practices on how to use identity processes to achieve zero trust capabilities identified in the [DHS CISA Zero Trust Maturity Model](https://zerotrust.cyber.gov/zero-trust-maturity-model/){:target="_blank"}{:rel="noopener noreferrer"}.

## Emerging cloud identity topics

The working group identified two emerging areas for ICAM program managers to consider. The first area is cloud infrastructure entitlement management, which is how entitlements are identified and managed in multi-cloud environments. An entitlement is a type of permission (e.g., Jane Doe has an entitlement to reset passwords. The password reset user interface service has an entitlement to access the password database resource). Cloud entitlement management is an emerging risk area for a privilege escalation attack which is an adversary technique to gain higher-level permissions from an unprivileged account. The second area is ICAM for DevSecOps. In high-velocity settings, the attack surface leveraged by an adversary may constantly change, putting the organization at extreme risk. The working group identified four best practices for DevSecOps teams to protect continuous improvement and delivery pipelines.

## Join our communities!

This playbook is iterative and agencies are encouraged to collaborate, share best practices, and lessons learned. Join the committee or community of practice linked below to learn and engage in Cloud, ICAM, and Zero Trust:

- [Join the Identity, Credential, and Access Management subcommittee (ICAMSC)](https://community.max.gov/pages/viewpage.action?pageId=234815732){:target="_blank"}{:rel="noopener noreferrer"}
- [Join the Cloud & Infrastructure Community of Practice](https://community.max.gov/display/Egov/CIO%2BCouncil%2BCloud%2Band%2BInfrastructure%2BCommunity%2Bof%2BPractice){:target="_blank"}{:rel="noopener noreferrer"}
