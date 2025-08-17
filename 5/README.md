# Finalize my Incident Handler’s Journal
In this activity, I finalized the incident handler's journal that I've been working on throughout this course. 
As I progressed through this course, I used my incident handler’s journal to apply my documentation skills and keep track of my learning journey. By now, I have multiple entries in my journal.

Scenario #1:
A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.
Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in the healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key.
The attackers were able to gain access to the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.
Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in its business operations. The company was forced to shut down its computer systems and contact several organizations to report the incident and receive technical assistance.

Scenario #2:
The scenario:
I am a level one security operations center (SOC) analyst at a financial services company. I received an alert about a suspicious file being downloaded on an employee's computer. 
I investigated this alert and discovered that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

Here is a timeline of the events leading up to this alert:
- 1:11 p.m.: An employee receives an email containing a file attachment.
- 1:13 p.m.: The employee successfully downloads and opens the file.
- 1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.
- 1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.

I retrieved the malicious file and created a SHA256 hash of the file. I recalled from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint.

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Now that I had the file hash, I used VirusTotal to uncover additional IoCs that are associated with the file.

Scenario #3:
I am a level-one security operations center (SOC) analyst at a financial services company. Previously, I received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified as malicious. Now that I had this information, I followed my organization's process to complete my investigation and resolve the alert.

My organization's security policies and procedures describe how to respond to specific alerts, including what to do when I receive a phishing alert. 
In the playbook, there is a flowchart and written instructions to help me complete my investigation and resolve the alert. At the end of my investigation, I updated the alert ticket with my findings about the incident.

Scenario #4: 
I recently joined the security team as a level-one security operation center (SOC) analyst at a mid-sized retail company. Along with its physical store locations, my company also conducts operations in e-commerce, which accounts for 80% of its sales.

I spent my first week of training becoming familiar with the company's security processes and procedures. Recently, the company experienced a major security incident involving a data breach of over one million users. Because this was a recent and major security incident, my team is working to prevent incidents like this from happening again. This breach happened before I began working at the company. I was asked to review the final report.
To gain an understanding of the incident's life cycle, my goals for the review are as follows:

Goal 1: Identify exactly what happened.

Goal 2: Identify when it happened. 

Goal 3: Identify the response actions that the company took.

Goal 4: Identify future recommendations

Scenario #5:
I am a security analyst working at the e-commerce store Buttercup Games. I was tasked with identifying whether there are any possible security issues with the mail server. To do so, I explored any failed SSH logins for the root account on Splunk. 

Scenario #6:
I am a security analyst at a financial services company. I received an alert that an employee received a phishing email in their inbox. I reviewed the alert and identified a suspicious domain name contained in the email's body: signin.office365x24.com. I needed to determine whether any other employees have received phishing emails containing this domain and whether they have visited the domain. I used Chronicle to investigate this domain.
