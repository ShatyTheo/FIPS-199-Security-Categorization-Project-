# FIPS-199-Security-Categorization-Project-

FIPS 199 Security Categorization Project – OPS System
Project Overview
This project documents the full FIPS 199 Security Categorization performed for the OneDrive Platform System (OPS) operated by the United States Agency of Data Security (UADS). The goal of this assessment was to determine the overall security impact level for OPS based on the types of information it stores, processes, and transmits.
The assessment follows federal standards:
•	FIPS 199 – Standards for Security Categorization of Federal Information and Information Systems
•	NIST SP 800 60 Vol. 1 & 2 – Mapping Information Types to Security Categories
# 1. System Description Review
The first step was to thoroughly analyze the OPS system description to understand its purpose, data flows, and information handled.
From the system description:
“OPS is a Microsoft service that connects you to all your files… OPS library is hosted on SharePoint Server in UADS Data Center… UADS uses OPS to store, process, and transmit Higher Education data, training and employment material… OPS contains the following user personal data: names and email addresses.”
## Key observations:
•	OPS is a major application hosted internally.
•	It stores Higher Education data, training and employment information, and user personal data (names, email addresses).
•	It functions as an information sharing platform.
•	No external system connections exist.
This analysis allowed identification of the system’s information types.
# 2. Identify Information Types
Using NIST SP 800 60 and the system description, the following information types were identified:
Information Types Present in OPS
1.	D.12.2 – Higher Education Information
2.	D.13.1 – Training and Employment Information
3.	C.3.5.9 – Information Sharing Information Type
4.	User Personal Data (PII): names and email addresses
“OPS contains the following user personal data: names and email addresses.”
These categories were used to determine provisional impact levels.
# 3. Determine Provisional Impact Levels
Using NIST SP 800 60 recommended values, provisional impact levels were assigned for each information type.
Example (from your completed assessment):
Information Type	Confidentiality	Integrity	Availability
Higher Education Data	Low	Low	Low
Training & Employment Data	Low	Low	Low
Information Sharing Data	N/A	N/A	N/A
These values reflect the baseline impact before system specific adjustments.
# 4. Obtain System Owner Concurrence
The provisional impact levels were reviewed with the System Owner to ensure:
•	Information types were correctly identified
•	Impact ratings reflected operational and mission needs
•	Business context was accurately represented
This step ensures the categorization aligns with organizational risk tolerance.
# 5. Adjust Impact Levels
Based on system owner feedback and the presence of PII, adjustments were made.
Example from your assessment:
Information Type	Adjusted Confidentiality	Rationale
Training & Employment Data	Moderate	Contains PII (names, emails), requiring stronger confidentiality protections
Supporting citation:
“OPS contains the following user personal data: names and email addresses.”
This justified raising confidentiality from Low → Moderate.
# 6. Determine Overall Security Impact
Following FIPS 199 rules:
The overall system impact level equals the highest impact among Confidentiality, Integrity, and Availability.
From your completed assessment:
•	Confidentiality: Moderate
•	Integrity: Low
•	Availability: Low

## Final System Security Category: MODERATE
This aligns with the final line of your assessment:
“Overall System Security Category: Moderate.”
Final Deliverables Included in This Project
# Conclusion
This project demonstrates a complete, audit ready FIPS 199 categorization aligned with federal standards and RMF best practices. It showcases practical GRC skills including documentation analysis, impact determination, stakeholder engagement, and compliance reporting.
