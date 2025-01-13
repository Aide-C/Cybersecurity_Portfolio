# Investigate a Suspicious File Hash
In this activity, I analyzed an artifact using VirusTotal and capture details about its related indicators of compromise using the Pyramid of Pain.
Previously, I was introduced to the concept of the Pyramid of Pain, which is used to understand the different types of indicators of compromise (IoCs). Remember, an IoC is observable evidence that suggests signs of a potential security incident. The Pyramid of Pain describes the relationship between IoCs and the level of difficulty that malicious actors experience when the IoCs are blocked by security teams.
VirusTotal is one of many tools that security analysts use to identify and respond to security incidents. VirusTotal is a service that allows anyone to analyze suspicious files, domains, URLs, and IP addresses for malicious content. Through crowdsourcing, VirusTotal gathers and reports on threat intelligence from the global cybersecurity community. This helps security analysts determine which IoCs have been reported as malicious. As a security analyst, you can take advantage of shared threat intelligence to learn more about threats and help improve detection capabilities. 

The scenario:
I am a level one security operations center (SOC) analyst at a financial services company. I received an alert about a suspicious file being downloaded on an employee's computer. 
I investigated this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

Here is a timeline of the events leading up to this alert:
- 1:11 p.m.: An employee receives an email containing a file attachment.
- 1:13 p.m.: The employee successfully downloads and opens the file.
- 1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.
- 1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.

I retrieved the malicious file and create a SHA256 hash of the file.I recalled from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint.

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Now that I had the file hash, I used VirusTotal to uncover additional IoCs that are associated with the file.