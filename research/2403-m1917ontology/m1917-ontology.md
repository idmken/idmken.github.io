````mermaid
graph LR

%% Top Node
id1(OMB M-19-17)

%% Identity Scope
id1.1(Enterprise)
id1.2(Public)

%% Policy Areas
id2.1(Adapt HSPD-12)
id2.2(Shift Operating Model)
id2.3(Improve Digital Interactions)

%% Components
id3.1(Governance)
id3.2(Architecture)
id3.3(Acquisition)

%% Tasks
id4.1(Implement NIST 800-63)
id4.2(Follow OPM PIV Eligibility)
id4.3(Require PIV)
id4.4(Accept Derived PIV)
id4.5(Manage and revoke access control)
id4.6(Use for Physical access)
id4.7(Use for Federation)
id4.8(Verify PIV from other agencies)
id4.9(Leverage existing PIV rather than issue new one)
id4.10(Maintain federation agreements)
id4.11(Digital Signature)
id4.12(Use Encryption)
id4.13(Enterprise ICAM governance structure)
id4.14(Cross-agency team)
id4.15(Chief Operating Officer leadership)
id4.16(Sub-component harmonization)
id4.17(Enterprise ICAM policy aligned with FICAM and CDM)
id4.18(Outline agency-wide performance expectations)
id4.19(Incorporate Digital Identity Risk Management)
id4.20(Authoritative solutions)
id4.21(Interoperable solutions)
id4.22(Manage non-person entities and automated technologies)
id4.23(Authoritative attribute sources privacy-enhanced API)
id4.24(Accept assertions from mission and business partners)
id4.25(Require contractor HSPD-12)
id4.26(Leverage HSPD-12 and ICAM approved Products)
id4.27(Leverage Best in Class, Tier 2, or shared services for digital certificates)
id4.28(CDM)
id4.29(Identity proofing)
id4.30(Limit PII collection and protect)
id4.31(Self-service Credential management)
id4.32(Leverage existing credentials and federations)
id4.33(Use federal or commercial shared services)
id4.34(Align with NIST SP 800-63)
id4.35(Share proofing confirmations to reduce proofing burden)
id4.36(Consumer feedback on new service providers)
id4.37(Multi-solution shared services)

%% Connect Nodes
%% Level 1
id1 --> id4.1 & id1.1 & id1.2

%%Level 2
id1.1 --> id2.1 & id2.2
id1.2--> id2.3
id2.1 --> id4.2 & id4.3 
id2.2 --> id3.1 & id3.2 & id3.3
id2.3 --> id4.29 & id4.30 & id4.31 & id4.32 & id4.33
id3.1 --> id4.13 & id4.17 & id4.18 & id4.19 & id4.24
id3.2 --> id4.20 & id4.21 & id4.22 & id4.23
id3.3 --> id4.25
id3.3 --> id4.26 & id4.27 & id4.28
id4.3 --> id4.4 & id4.5 & id4.6 & id4.7 & id4.11 & id4.12
id4.7 --> id4.8 & id4.9 & id4.10
id4.13 --> id4.14 & id4.15 & id4.16
id4.33 --> id4.34 & id4.35 & id4.36 & id4.37
