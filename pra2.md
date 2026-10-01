PRACTICAL 2 — PRIVACY IMPACT ASSESSMENT OF CHATGPT
1. Aim
To conduct a Privacy Impact Assessment of ChatGPT by identifying personal-data processing activities, assessing associated privacy risks, and defining appropriate mitigation controls.

2. Assessment Parameters
Parameter	Description
System	ChatGPT
Organization	OpenAI
Technology	Artificial Intelligence / Large Language Model
Primary Users	Individuals and organizations
Primary Processing	User prompts, content, account and technical information
Assessment Focus	Personal-data privacy
Assessment Basis	OpenAI Privacy Policy supplied for analysis

3. Data-Flow Model
USER
  │
  │ Account Information / Prompts / Files / Other Content
  ▼
CHATGPT APPLICATION
  │
  │ Authentication / Service Interaction / Technical Data
  ▼
OPENAI SERVICES
  │
  ├── AI Processing
  ├── Security & Abuse Prevention
  ├── Service Operations
  ├── Support
  ├── Analytics / Other Functions
  │
  ▼
GENERATED RESPONSE
  │
  ▼
USER

Additional processing may involve vendors, service providers, affiliates, and third-party services depending on the feature or interaction.

4. Personal Data Processing Matrix
Data	Source	Processing Activity	Potential Privacy Risk
Account information	User	Account management	Unauthorized access
Prompts/content	User	AI processing/service improvement as applicable	Sensitive-data disclosure
Files/images/audio/video	User	AI processing	Confidentiality loss
Communication data	User	Support/communication	Unauthorized access
Contact data	User device	Contact functionality	Third-party privacy
IP/log data	Device	Security/service operation	Tracking/privacy exposure
Usage data	Service interaction	Analytics/service improvement	Profiling
Device data	Device	Service operation/security	Device identification
Location data	Device/IP	Security/personalization	Location exposure
Payment data	User/payment process	Transaction processing	Financial privacy

5. Privacy Risk Analysis
ID	Risk Scenario	Cause	Potential Impact	Likelihood	Impact
P01	Sensitive information entered into prompts	User disclosure	Privacy/confidentiality harm	M	H
P02	Excessive data uploaded	Lack of minimization	Unnecessary processing	M	H
P03	Account compromise	Credential theft	Conversation exposure	M	H
P04	Conversation shared externally	User action	Unauthorized disclosure	M	H
P05	Third-party processing	Service dependencies	Additional data exposure	M	H
P06	Cross-border processing	Global infrastructure	Jurisdictional complexity	M	M
P07	Extended retention	Legal/security exceptions	Longer exposure period	M	M
P08	Contact-data processing	Address-book integration	Third-party privacy impact	L/M	M
P09	Advertising-related processing	Ad personalization	Profiling/privacy concern	M	M
P10	Human error	Incorrect configuration/use	Accidental disclosure	M	H

6. Risk Treatment Plan
Risk ID	Control	Control Type	Residual Risk
P01	Redaction and minimization	Preventive	Medium
P02	Data-minimization guidance	Preventive	Medium
P03	Strong authentication/MFA	Preventive	Low/Medium
P04	Sharing awareness and controls	Preventive	Medium
P05	Vendor due diligence	Preventive/Detective	Medium
P06	Legally valid transfer mechanisms	Preventive	Medium
P07	Retention/deletion controls	Preventive	Medium
P08	User choice before contact access	Preventive	Low/Medium
P09	Advertising controls	Preventive	Medium
P10	User/employee privacy training	Preventive	Medium

7. Privacy-by-Design Assessment
Principle	Application to ChatGPT	Assessment
Data Minimization	Users can limit information supplied to the service	Required at user and organizational level
Purpose Limitation	Policy specifies processing purposes	Documented
Transparency	Privacy Policy describes collection and use	Documented
User Control	Deletion, export, memory and other controls	Available
Security	Technical, administrative and organizational safeguards	Documented
Retention Limitation	Deletion and Temporary Chat mechanisms	Documented with exceptions
Accountability	Privacy requests and erasure records	Documented
Privacy by Default	User settings determine certain processing choices	Requires ongoing review

8. Data Subject/User Rights Assessment
Right/Control	PIA Relevance	Available Mechanism
Access	Enables understanding of processed data	Privacy request
Rectification	Corrects personal information	Privacy request
Erasure	Reduces retained personal data	Deletion tools/request
Restriction	Limits certain processing where applicable	Privacy request
Portability	Allows retrieval/transfer of data	Export/request
Consent withdrawal	Applies where consent is the legal basis	Privacy request
Model-improvement choice	Controls certain use of content	Account settings
Temporary Chat	Limits persistence/history	ChatGPT setting

9. Residual Risk Assessment
After implementation of the proposed controls, certain risks remain:

Residual Risk	Reason
User disclosure	Users may voluntarily provide sensitive information
Cybersecurity	No online system can eliminate all security threats
Human error	Incorrect sharing or configuration remains possible
Third-party dependency	Service operations may involve external providers
Legal complexity	Privacy requirements differ across jurisdictions
Retention exceptions	Legal/security requirements may require continued retention

10. PIA Action Plan
Priority	Action	Responsible Function*	Frequency
High	Review personal-data inventory	Privacy/Data Governance	Periodic
High	Review sensitive-data risks	Privacy + Security	Periodic
High	Assess third-party processors	Procurement/Privacy	Periodic
High	Test incident-response procedures	Security	Periodic
Medium	Review retention schedules	Privacy/Legal	Periodic
Medium	Review user privacy controls	Product/Privacy	Periodic
Medium	Conduct privacy training	HR/Compliance	Periodic
Medium	Reassess new AI features	Privacy/Product	Before deployment

*Responsible functions are proposed roles for a PIA framework, not a statement about OpenAI's internal organizational structure.

11. PIA Outcome
Area	Assessment
Data volume	High variability due to user-generated content
Data sensitivity	Potentially high
Processing complexity	High
Third-party involvement	Present
Cross-border processing	Present
User controls	Multiple controls described
Deletion mechanisms	Available with stated exceptions
Security controls	Technical, administrative and organizational measures stated
Residual privacy risk	Present and requires continuous management

12. Conclusion
The PIA identifies user-generated content, sensitive information disclosure, account security, third-party processing, international data transfers, retention, and accidental sharing as key privacy-risk areas associated with ChatGPT.

The principal mitigation strategy is a combination of data minimization, user control, access security, retention management, vendor governance, transparency, and continuous privacy assessment.

The PIA should be treated as a living assessment and revisited when significant changes are made to the system, data-processing activities, user population, or applicable regulatory requirements.

