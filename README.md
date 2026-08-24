Digital Forensics: Evidence Acquisition, Preservation, Analysis and Reporting

1.Introduction

Digital forensics is the process of collecting, preserving, examining, and analyzing digital evidence from computers, mobile phones, storage devices, and networks. It helps investigators understand what happened during a digital incident or cybercrime. Proper evidence acquisition, preservation, analysis, and reporting are important to maintain the accuracy and integrity of digital evidence. Digital forensics follows a systematic process so that the evidence can be properly documented and presented as reliable findings.

2. Objectives
The main objectives of this portfolio are:
To understand the digital forensic investigation process.
To document the acquisition of digital evidence.
To preserve evidence without changing its original state.
To analyze digital evidence systematically.
To maintain proper evidence documentation and chain of custody.
To prepare a clear and professional forensic report.



Digital Forensic Investigation Process
The major stages of a digital forensic investigation are:
Identification → Acquisition → Preservation → Examination → Analysis → Documentation → Reporting

Evidence Identification
Evidence identification is the first step. Investigators determine what devices and digital information may contain useful evidence.
Possible Sources of Digital Evidence
Desktop computers
Laptops
Mobile phones
USB drives
Hard disks and SSDs
Memory cards
Network logs
Email records
Cloud storage
Application logs
Browser history
The investigator should record the device description, identification number, condition, location, date, and time.

Evidence Acquisition
Evidence acquisition means creating a forensic copy of the original digital evidence for examination.
The original device should be protected from unnecessary modification. Whenever possible, investigators use a write blocker to prevent data from being written to the evidence device.

Important Acquisition Information
The investigator should document:
Evidence ID
Device type
Make and model
Serial number
Storage capacity
Acquisition date and time
Acquisition method/tool
Investigator name
Hash value
Any errors encountered
Example
A forensic image of a USB drive can be created and stored as an evidence file. The investigator then calculates a cryptographic hash such as SHA-256.
If the hash of the acquired image is recorded as:
SHA-256: [Recorded Hash Value]
the value can later be checked to determine whether the forensic image has changed.

Important Acquisition Information
The investigator should document:
Evidence ID
Device type
Make and model
Serial number
Storage capacity
Acquisition date and time
Acquisition method/tool
Investigator name
Hash value
Any errors encountered
Example
A forensic image of a USB drive can be created and stored as an evidence file. The investigator then calculates a cryptographic hash such as SHA-256.
If the hash of the acquired image is recorded as:
SHA-256: [Recorded Hash Value]
the value can later be checked to determine whether the forensic image has changed.

Evidence Preservation
Evidence preservation ensures that digital evidence remains unchanged and protected from accidental or intentional modification.
Preservation Methods
Keep the original device secure.
Use write protection when appropriate.
Create verified forensic images.
Calculate and record cryptographic hashes.
Store evidence in a controlled location.
Restrict access to authorized personnel.
Maintain a chain-of-custody record.

Hashing
Hashing is an important technique used to verify the integrity of digital evidence.
A hash function converts digital data into a fixed-length value. Even a small change in the data normally produces a different hash value.
Common hashing algorithms include:
MD5
SHA-1
SHA-256
For modern forensic integrity verification, SHA-256 is commonly preferred.

Chain of Custody
The chain of custody is a chronological record showing who handled the evidence, when it was handled, why it was handled, and where it was stored. Maintaining the chain of custody helps demonstrate that evidence was properly controlled throughout the investigation.

Evidence Analysis
Analysis is the process of interpreting the collected digital evidence to determine relevant facts.
The analysis should be performed on a forensic copy rather than unnecessarily modifying the original evidence.
Areas of Analysis
File systems
Deleted files
Browser activity
Metadata
User activity
System logs
Application data
USB device history
Email information
Timestamps
Network information
Example Analysis
Suppose a forensic image contains browser history showing access to a particular website.

Documentation
Proper documentation is essential throughout the investigation.
The investigator should document:
Evidence identification
Collection procedure
Acquisition method
Hash values
Tools used
Analysis steps
Important findings
Screenshots where appropriate
Errors or limitations
Chain of custody
Final conclusions
Documentation should be clear, objective, accurate, and reproducible.

Forensic Tools
Different tools can be used depending on the type of investigation.
Examples include:
Autopsy
The Sleuth Kit
FTK
EnCase
Wireshark
Volatility
Magnet AXIOM
The tool name, version, purpose, and relevant settings should be documented in the forensic report.

Conclusion
Digital forensics provides a systematic method for investigating digital incidents and handling electronic evidence. The reliability of an investigation depends on proper acquisition, preservation, analysis, documentation, and reporting.
Maintaining evidence integrity, recording the chain of custody, using appropriate forensic tools, and clearly documenting every important action helps make the investigation reliable and reproducible. A well-prepared forensic portfolio therefore provides a complete record of how digital evidence was handled from collection to final reporting.

References
National Institute of Standards and Technology (NIST), Guide to Integrating Forensic Techniques into Incident Response.
National Institute of Standards and Technology (NIST), Guidelines on Mobile Device Forensics.
The Sleuth Kit and Autopsy Digital Forensics Platform documentation.
Scientific Working Group on Digital Evidence (SWGDE), digital evidence best-practice guidance.
<img width="1600" height="1032" alt="WhatsApp Image 2026-08-24 at 2 34 48 PM" src="https://github.com/user-attachments/assets/ed2580b0-7237-4c44-aee9-a0fb92f328a4" />
<img width="1599" height="854" alt="WhatsApp Image 2026-08-24 at 2 34 11 PM" src="https://github.com/user-attachments/assets/c4ff72bf-563a-42de-b0a0-06e433e69671" />
<img width="1599" height="1288" alt="WhatsApp Image 2026-08-24 at 2 33 25 PM" src="https://github.com/user-attachments/assets/92b5866b-7621-4fe4-a56e-16c8b23503f6" />
<img width="1600" height="953" alt="WhatsApp Image 2026-08-24 at 1 43 50 PM (1)" src="https://github.com/user-attachments/assets/7d128026-6a20-4609-b45e-24d5907fa68e" />


