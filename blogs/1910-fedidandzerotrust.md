Reproduced here from the [ISACA GWDC Blog site](https://isaca-gwdc.org/federal-identities-and-zero-trust/){:target="_blank"}{:rel="noopener noreferrer"}

October 31, 2019

# Federal Identity and Zero Trust

Managing federal identities in a zero trust environment is the direction the Federal Government is moving with the Office of Management and Budget (OMB) memo 19-17. [Enabling mission delivery through Identity, Credential, and Access Management (ICAM)](https://www.whitehouse.gov/wp-content/uploads/2019/05/M-19-17.pdf){:target="_blank"}{:rel="noopener noreferrer"} is a seminal policy update which not only introduces a continued direction for federal identity management but also removed lingering policy debt.

## Moving Beyond Smart Cards

Historically, federal identity management has focused on credentials. A government employee or contractor completes a background check before employment and is issued a Homeland Security Presidential Directive (HSPD) 12 compliant credential, usually a Personal Identity Verification (PIV) card. Is this one form factor sufficient and cost-effective? Many federal agencies have pushed back that a PIV is excellent for high assurance activities, BUT not all transactions are high risk! PKI authentication and signature are also not always cloud friendly. Managing federal identities in a zero trust environment will require new technology, policies, and procedures.

This memo now allows agencies to start exploring the use of HSPD-12 compliant non-smart card-based credentials. Agencies can now pilot other credential types such as FIDO compliant hardware tokens or derived software-based tokens in collaboration with the Federal CIO Council and the National Institute for Standards and Technology (NIST). PIV and the DoD Common Access Card (CAC) will remain as the high assurance option, but now agencies have the flexibility to use non-smart card credentials and still be compliant.

## Managing ~~Credentials~~ Identities

Managing identities (not just credentials) is critical in decreasing transaction risks. Identity management involves the complete lifecycle from [identity proofing to deactivation](https://arch.idmanagement.gov/services/identity/){:target="_blank"}{:rel="noopener noreferrer"}. Managing identities in a modern government include managing multiple identities for the same person or maybe a thing, like a device, across multiple on-premise or cloud platforms. A fundamental shift in this policy is moving away from the obsolete Level of Assurance model outlined in OMB Memo 04-04 toward a business and privacy management risk model based on mission needs. This new model outline in [NIST 800-63-3, Digitial Identity Guidelines](https://pages.nist.gov/800-63-3/sp800-63-3.html){:target="_blank"}{:rel="noopener noreferrer"}, separates the individual identity assurance elements into discrete components of identity, assurance, and federation. Expect to see formal guidance on how to securely federate coming in the next couple of years. There are also separate processes when managing federal identities versus citizen or mission partner identities.

## Zero Trust Operating Model

Shifting beyond the perimeter is the ultimate goal of this new policy when managing federal identities, but also consumer identities. Why? There is no perimeter, and your security risk model must adapt. Federal Agencies are no different in their threat landscape, security needs, and budget constraints from private corporations. Agencies deliver critical citizens services from taking care of veterans, providing weather services, ensuring our borders are safe, and thousands of other crucial duties. That means government employees are remote, in the field, in an office, somewhere in the world, and they need secure access to government information. This memo lays the foundation to harmonize an enterprise-wide approach to identity governance, architecture, and acquisition, and recognizing identities are a critical component. Some of the more fundamental changes introduced in this memo include the following.

- Ensure agency ICAM policies align with the Federal ICAM architecture and DHS Continuous Diagnostic and Monitoring (CDM) requirements.
- Incorporate NIST 800-63-3 Identity Risk Management into agency processes, including non-federal users such as citizens and mission partners.
- Establish authoritative ICAM services both within the agency and government-wide.
- Ensure ICAM capabilities are interchangeable, leveraging commercially available products and Application Programming Interfaces (API).
- Manage non-person entities (NPE) for technologies such as Robotic Process Automation (RPA) and Artificial Intelligence (AI).
- Reinforces the buy, not-build mentality with using either federal or commercial shared shares.
- Rescinds several key OMB Identity memos such as M-04-04, E-Authentication Guidance for Federal Agencies, M-05-05, Electronic Signatures: How to Mitigate the Risk of Commercial Managed Services, 0MB Memorandum, Requirements/or Accepting Externally-Issued Identity Credentials, and a few others.

The recent [NIST draft Special Publication 800-207, Zero Trust Architecture](https://csrc.nist.gov/publications/detail/sp/800-207/draft){:target="_blank"}{:rel="noopener noreferrer"}, also brings M-19-17 full circle in aligning multiple government programs such as DHS CDM and the Trusted Internet Connection (TIC) in a single Zero Trust Architecture. The proposed Zero Trust Architecture may help agencies consolidate investment across multiple programs and align mission needs across multiple offices to increase security and citizen-facing services which is the ultimate intent of M-19-17.

If you’re interested in federal security, don’t forget to check out the [GWDC calendar of events](https://isaca-gwdc.org/events/){:target="_blank"}{:rel="noopener noreferrer"}. 
