PRACTICAL 1 — DATA PRIVACY AUDIT OF OPENAI
1. Aim
To assess OpenAI's personal-data processing practices against core data-privacy principles by reviewing its published Privacy Policy, with emphasis on data collection, purpose, disclosure, retention, user control, rights, security, and privacy risks.

2. Objectives
No.	Objective
1	Identify categories and sources of personal data collected.
2	Examine stated purposes of personal-data processing.
3	Assess disclosure and third-party processing practices.
4	Examine retention, deletion, and user-control mechanisms.
5	Identify privacy risks associated with the stated practices.
6	Document privacy controls and areas requiring continued assessment.

3. Audit Scope
Domain	Areas Examined
Data Collection	Account, content, communication, contact, log, usage, device and location data
Processing	Service delivery, personalization, research, improvement, security, marketing
Disclosure	Vendors, service providers, marketing partners, affiliates, authorities
Retention	Deletion, Temporary Chat, legal/security exceptions
User Controls	Export, deletion, memory, training/model-improvement controls
Data Subject Rights	Access, rectification, deletion, restriction, portability, consent withdrawal
Security	Technical, administrative and organizational safeguards
Transfers	Processing across multiple jurisdictions
Special Categories	Children's data and age-related controls

4. Data Inventory
Data Category	Examples Identified in Policy	Collection Source	Privacy Significance
Account Data	Name, contact details, credentials, DOB, payment data	User	High
User Content	Prompts, files, images, audio, video	User	High
Communication Data	Messages and contact information	User	Medium
Contact Data	Device address-book information	User/device	High
Log Data	IP address, browser, request time	Device/browser	Medium
Usage Data	Features, interactions, feedback, access information	Service interaction	Medium
Device Data	Device name, OS, identifiers, browser	Device	Medium
Location Data	General location; optional precise location	Device/service	High
Cookie Data	Preferences, authentication information	Device/browser	Medium
External-Source Data	Security, marketing and publicly available information	Third parties/public sources	Variable

5. Processing Purpose Assessment
Stated Purpose	Examples	Privacy Principle Relevant
Service provision	Responding to ChatGPT requests	Purpose limitation
Service improvement	Developing features and models	Transparency, control
Research	Research and analysis	Purpose limitation
Personalization	Customized content/experience	Data minimization
Advertising	Personalization/measurement for Free and Go users	Transparency, user controls
Communication	Service-related communications	Purpose limitation
Security	Fraud, abuse and threat prevention	Security
Legal compliance	Meeting legal obligations	Lawfulness
Protection of rights	Protecting users, OpenAI and third parties	Necessity/proportionality

6. Data Disclosure Assessment
Recipient	Purpose/Function	Data Access Characteristic	Privacy Consideration
Vendors	Business operations	Process/store data according to instructions	Third-party risk
Service Providers	Hosting, cloud, support, safety, analytics etc.	Operational processing	Vendor governance
Marketing Partners	Promotion and effectiveness measurement	Limited information	Transparency/control
Affiliates	Consistent with policy	Internal group sharing	Governance
Government Authorities	Legal/security requirements	Circumstantial	Legal basis
Business Administrators	Enterprise/business account administration	May access account/content	Organizational confidentiality
Third-party Services	Search, shopping and other interactions	User-initiated sharing	External privacy policies
Transaction Counterparties	Corporate transactions	Due diligence/transfer	Data-transfer governance

7. Retention and Deletion Audit
Mechanism	Policy Position	Assessment
General retention	Retained as necessary for services or legitimate business purposes	Purpose-based
User deletion	Users can delete chats, memories and accounts	Control available
Deletion timeline	Personal data generally removed within 30 days after deletion request	Defined timeframe, subject to exceptions
Temporary Chat	Automatically deleted within 30 days, subject to exceptions	Reduced-retention option
Legal retention	Data may be retained when legally required	Exception
Security/fraud retention	Certain data may be retained to address abuse/security	Exception
Financial records	Transaction information may be retained	Regulatory/business requirement
Erasure records	Audit record of deletion request may be retained	Accountability mechanism

8. User Privacy Controls
Control	Availability According to Policy	Privacy Objective
Model-improvement control	Yes	User choice
Memory control	Yes	Data minimization/personalization control
Data export	Yes	Data portability
Chat deletion	Yes	User control
Account deletion	Yes	Erasure
Temporary Chat	Yes	Reduced persistence
Cookie controls	Depending on applicable law	Tracking control
Advertising controls	Available to Free and Go users	Advertising transparency/control
Marketing unsubscribe	Yes	Communication control

9. Data Subject Rights
Right	Stated in Policy	Mechanism
Access	Yes, subject to applicable law	Account/privacy request
Rectification	Yes	Privacy request
Erasure	Yes	Account/privacy request
Restriction	Yes, subject to applicable law	Privacy request
Data portability	Yes, subject to applicable law	Data controls/request
Withdrawal of consent	Where consent is legal basis	Privacy request
Complaint	Yes	Local data protection authority
Correction/removal of inaccurate information	Addressed in policy	Privacy request

10. Security Control Assessment
Control Area	Policy Statement	Audit Observation
Technical safeguards	Implemented	Control exists
Administrative safeguards	Implemented	Control exists
Organizational safeguards	Implemented	Control exists
Unauthorized access	Protection stated	Control objective identified
Data disclosure	Protection stated	Control objective identified
Data alteration/destruction	Protection stated	Control objective identified
Transmission security	Policy acknowledges inherent internet/email risks	Residual risk remains

11. Privacy Risk Register
ID	Risk	Likelihood	Impact	Risk Level	Recommended Control
R01	Excessive personal information submitted in prompts	M	H	High	Data minimization/user guidance
R02	Sensitive information uploaded by users	M	H	High	Redaction/anonymization
R03	Unauthorized account access	M	H	High	Strong authentication/MFA
R04	Accidental sharing with third parties	M	H	High	User confirmation/awareness
R05	Third-party processing	M	H	High	Vendor due diligence
R06	Cross-border processing	M	M	Medium	Transfer safeguards
R07	Extended retention under exceptions	M	M	Medium	Retention governance
R08	Processing of contact information of non-users	L/M	M	Medium	Consent/notice governance
R09	Advertising-related processing	M	M	Medium	Transparency and controls
R10	Human error	M	H	High	Training and privacy-by-design

Legend: L = Low, M = Medium, H = High.

12. Audit Findings
Finding ID	Finding	Evidence in Policy	Assessment
F01	Broad categories of personal data are collected	Sections 1–2	Requires strong data governance
F02	Multiple processing purposes are disclosed	Section 2	Purposes are documented
F03	Multiple third-party recipient categories exist	Section 3	Vendor/third-party governance is important
F04	Deletion mechanisms are available	Sections 4–5	Positive user-control mechanism
F05	Retention exceptions exist	Section 4	Requires retention governance
F06	Multiple user rights are recognized	Section 6	Rights-management mechanism exists
F07	International processing occurs	Section 6	Cross-border transfer controls required
F08	Security safeguards are stated	Section 8	Security framework is described
F09	Children's privacy provisions exist	Section 7	Age-related safeguards are documented

13. Recommendations
Priority	Recommendation	Expected Outcome
High	Strengthen user data-minimization guidance	Reduced unnecessary disclosure
High	Maintain strong authentication and account security	Reduced account-compromise risk
High	Continue third-party/vendor privacy assessments	Reduced processor risk
High	Maintain clear retention schedules	Controlled data lifecycle
Medium	Periodically review privacy controls	Improved user awareness
Medium	Strengthen organizational AI-use policies	Reduced employee-related privacy risks
Medium	Conduct periodic privacy impact assessments	Continuous risk management

14. Conclusion
The audit indicates that OpenAI's Privacy Policy provides a comprehensive description of personal-data categories, processing purposes, disclosures, retention mechanisms, user controls, privacy rights, international processing, children's privacy, and security measures.

The principal privacy-risk areas identified are user-provided sensitive information, account security, third-party processing, retention exceptions, cross-border processing, and accidental disclosure.

The audit therefore recommends continued emphasis on data minimization, access control, vendor governance, retention management, transparency, and user privacy controls.
