# Identity and Access Management Competency Model

This model is based on my dissertation research, earlier work developed as part of the U.S. Federal Government Identity Governance Framework and industry knowledge.

Outline digital identity core competencies to create a standardized understanding and approach to digital identity competencies.

## References
1. FICAM Playbooks
2. ICAM Governance Framework - Competency Model Table 4, Page 15
3. NIST Workforce Framework for Cybersecurity (NICE Framework)
4. NIST NICE Task Knowledge Skill (TKS) Statement Authoring Guide for Workforce Frameworks – Working Draft

## Process Overview/Scope

This competency model aligns with the FICAM architecture services framework in the context of the NIST NICE Framework Tasks Knowledge Skills (TKS) statement authoring guide. TKS statements are the core building blocks of a workforce framework model. Every organization executes common tasks as well as some context-unique tasks. A workforce framework provides organizations a way to describe their work through Task statements. Similarly, a workforce framework provides a way to describe learners via Knowledge and Skill statements. Statements are defined in three ways.
1.	Task statements: Describe the work to be done; they represent a collection of associated concepts and actions defined by Knowledge and Skill statements.
2.	Knowledge statements: Describe a retrievable set of concepts within a learner’s memory—that is, what a learner knows.
3.	Skill statements: Describe what the learner can do

Statements are created around five principles.
1.	Flexible: The statements can be applied or combined in various ways to address different circumstances and needs. 
2.	Consistent: The statements are drafted following these five principles.
  a.	Good Skill Statement: Skill in preparing test and evaluation reports.
  b.	Bad Skill Statements:
      i.	Skill in test and evaluation reports.
      ii.	Preparing test and evaluation reports.
  c.	Rationale: In the first bad example above, the statement starts with “Skill in” but omits the verb that indicates the action to be taken, introducing confusion—there may be multiple skills associated with test and evaluation reports (e.g., creating, conducting, assessing). While the second incorrect statement includes the verb “Preparing,” by excluding “Skill in” at the start it renders the statement less recognizable as a Skill statement and, further, transforms what should be a skill into a task.
3.	Clear: The statements are easy to read and understand, and not overly complex or lacking clarity. 
    a.	Good Knowledge Statement: Knowledge of vulnerability information dissemination sources (e.g., vendor alerts, government advisories, product literature errata, and sector bulletins). 
    b.	Bad Knowledge Statement: Vulnerability information dissemination sources (e.g., vendor alerts, government advisories, product literature errata, and sector bulletins). 
    c.	Rationale: Including the “Knowledge of” phrase distinguishes the statement from being a task or skill statement.
4.	Affirmative: The statements are structured in an affirmative (i.e., grammatically positive) form to assist with the design and evaluation of performance metrics and goals and to minimize issues with language translation for organizations that work with multi-lingual teams. This is in contrast to grammatically negative statements that use language such as “do not” or “avoid.”
    a.	Good Task Example: Identify privacy compliance obligations.
    b.	Bad Task Example: Ensure privacy compliance obligations are identified.
    c.	Rationale: Using “Ensure” may create confusion and is ambiguous.
5.	Discrete: The statements should not include more than one (compound) idea
    a.	Good Task Statement: Identify organizational data elements.
    b.	Bad Task Statement: Identify, classify, or document organizational data elements in 
    c.	physical or digital form.
    d.	Rationale: As written, the bad Task statement contains multiple activities (i.e., identify, classify, document) that should be broken down into three discrete Task statements, one

## Key Assumptions
The FICAM architecture contains five service areas. The FICAM governance area is integrated into identity management. Parts of the FICAM federation area are integrated into Access Management.

## Procedures

Each statement includes an identifier based on 

<service area - statement area - number>

For example:

-	IK1 = Identity Management Knowledge Statement 1
-	CT2 = Credential Management Task Statement 2
-	AK4 = Access Management Knowledge Statement 4
-	GS3 = Governance Knowledge Statement 3

## Identity Management

Identity Management is how an organization collects, verifies, manages attributes, and entitlements to establish and maintain a binding between a user and their real identity.

Table 1. Identity management TKSs

| Identifier | Statement | Resources |
| ---- | ---- | ----- |
| IK1 |	Knowledge of identity lifecycle management.	| 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/) |
| IK2 | Knowledge of identity proofing methods, trust lengths, strengths and weaknesses. | - |	
| IK3 | Knowledge of identity directory technology and services. | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)|
| IK4 | Knowledge of identity resolution technology and techniques.	| - |
| IK5 | Knowledge of privacy laws related to personal information data collection, aggregation, and maintenance. |	1. [ICAM Policy Matrix](https://www.idmanagement.gov/university/policymatrix/) |
| IK6 | Knowledge of entitlements management and workflows. | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)|
| IK7 | Knowledge of identity fraud tactics, techniques, and procedures. | - |
| IS1 | Skill in performing identity lifecycle management. | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)|
| IS2 | Skill in identifying the components required to complete an identity proofing process aligned to an Identity Assurance Level (IAL). | - |
| IS3 | Skill in configuring and maintaining an identity directory service. | - |
| IS4 | Skill in applying techniques to resolve the combination of identity attributes to a unique person. | - |
| IS5 | Skill in preparing and executing access reviews and recertifications. | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)|
| IS6 | Skill in managing entitlements. | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)|
| IS7 | Skill in identifying identity fraud TTPs given an identity proofing process. | - |	
| IS8 | Skill in assessing identity proofing process for potential fraud. | - |
| IT1 | Perform identity proofing activities at various IALs. | - |
| IT2 | Develop an identity directory maintenance plan. | - |
| IT3 | Implement a process to review identity information for currency and accuracy. | - |	
| IT4 | Implement a redress process. | - |
| IT5 | Conduct role and group modeling. | - |
| IT6 | Create and automate identity lifecycle workflows (provisioning, entitlements management, identity records management, and end-user activity notifications (e.g., expiring credentials)). | 1. [U.S. Federal ILM Playbook](https://www.idmanagement.gov/playbooks/ilm/)<br>2. [IDPro Bok Overview of Digital Identity Lifecycle](https://bok.idpro.org/article/id/31/)<br>3. [IdPro BoK User Provisioning](https://bok.idpro.org/article/id/84/)|
| IT7 |	Identify identity fraud indicators given an identity proofing process. | - |

## Credential Management

Credential Management is how an organization issues, manages, and revokes credentials bound to users or accounts.

Table 2. Credential management TKSs

| Identifier | Statement | Resources |
| --- | --- | ---
| CK1 | Knowledge of credential lifecycle management. | 1. [U.S. Federal ICAM Architecture](https://www.idmanagement.gov/arch/) |
| CK2 | Knowledge of authenticator types, strengths, and weaknesses aligned with Authenticator Assurance Level (AAL). | - |
| CK3 | Knowledge of authenticator binding techniques. | - |	
| CK4 | Knowledge of Federal Public Key Infrastructure (FPKI) credential types. | 1. [U.S. Federal PKI 101](https://www.idmanagement.gov/university/fpki/#fpki-third-party-trust)<br>2. [IDPro Practical Implication of PKI](https://bok.idpro.org/article/id/80/) |
| CK5 | Knowledge of Fast Identity Online (FIDO) standards and Web Authentication (WebAuthN). | - |	
| CS1 | Skill in identifying an authenticator to an AAL. | - |
| CS2 | Skill in binding various authenticators to directory records. | - |		
| CS3 | Skill in performing credential lifecycle management. | - |
| CS4 | Skill in implementing FIDO authenticators. | - |
| CT1 | Implement and maintain a credential registration process across various types of authenticators. | - |
| CT2 | Bind an authenticator to an identity across various AAL. | - |
| CT3 | Perform credential lifecycle management actions such as activate, renew, reset, suspend, revoke, or terminate. | -  | 
| CT4 | Issue and maintain PKI credentials. | - |

## Access Management

Access Management is how an application authenticates and authorizes a user for appropriate access to applications or data.

Table 3. Access management TSKs

| Identifier | Statement | Resources | 
| --- | --- | --- |
| AK1 | Knowledge of the difference between authentication and authorization. | 1. [U.S. Federal ICAM Architecture](https://www.idmanagement.gov/arch/) |
| AK2 | Knowledge of cloud authentication protocols aligned to Federation Assurance Level (FAL). | - |	
| AK3 | Knowledge of authorization “access” models. | 1. [U.S. Federal ICAM Architecture](https://www.idmanagement.gov/arch/)  |
| AK4 | Knowledge of privilege access management. | 1. [U.S. Federal Privileged Identity Playbook](https://www.idmanagement.gov/playbooks/pam/) |
| AK5 | Knowledge of the two-step authentication process. | 1. [U.S. Federal ICAM Architecture](https://www.idmanagement.gov/arch/)  |
| AK6 | Knowledge of secure sharing of validated attributes. | - |		
| AS1 | Skill in identifying an appropriate authorization model based on the use case. | - |
| AS2 | Skill in implementing authentication techniques. | - |
| AS3 | Skill in managing access requirements using a policy decision and enforcement point. | - |	
| AS4 | Skill in implementing and managing privileged access management tools. | - |
| AS5 | Skill in troubleshooting access-related issues. | - |
| AT1 | Configure and manage single sign-on (SSO) services using federation protocols such as SAML and OIDC. | - |
| AT2 | Configure directory and agent integration with SSO. | - |
| AT3 | Troubleshoot federation protocol errors.  | - |
| AT4 | Operate and manage policy decisions and enforcement points. | - |
| AT5 | Integrate a partner application. | - |

## Governance

Governance is the policies and processes that allow an organization to accept digital identities, attributes, and credentials managed by someone else. This could also be called Federation.

Table 4. Governance TKSs

| Identifier | Statement | Resources |
| --- | --- | --- |
| GK1 | Knowledge of the digital identity risk assessment (DIRA) process. | 1. [Federal U.S. DIRA Playbook](https://www.idmanagement.gov/playbooks/dira/) |
| GK2 | Knowledge of aligning IAM capabilities to DIRA results. | - |
| GS1 | Skill in performing a DIRA. | 1. [Federal U.S. DIRA Playbook](https://www.idmanagement.gov/playbooks/dira/) |
| GS2 | Skill in aligning DIRA results to IAM capabilities. | - | 		
| GT1 | Review a DIRA conducted by a partner organization. | 1. [Federal U.S. DIRA Playbook](https://www.idmanagement.gov/playbooks/dira/) |
| GT2 | Lead a DIRA with a partner organization. | 1. [Federal U.S. DIRA Playbook](https://www.idmanagement.gov/playbooks/dira/) |
