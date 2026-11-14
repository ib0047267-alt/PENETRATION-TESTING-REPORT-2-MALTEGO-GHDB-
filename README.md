# PENETRATION-TESTING-REPORT-2-MALTEGO-GHDB-
PENETRATION TESTING REPORT
PENETRATION TESTING REPORT
FOOTPRINTING & INFORMATION GATHERING PHASE
W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS
Report Details	Information
Pentester Name (Cybersecurity Professional)	Ibrahim Abimbola Bello
Program/Batch	B084-Networkwalks
Modules Completed	Footprinting with GHDB; Footprinting with Maltego
Client/Target	Networkwalks (authorized educational target)
Permission secured from client?	Yes – within the authorized lab scope
Phases Covered	Phase 1: Reconnaissance & Footprinting
________________________________________
1. Liability Disclaimer
I have performed these activities only on systems and domains where I had secured the necessary authorization or within the scope of the assigned educational practical exercises.
All materials presented in this report are for educational and research purposes only. The knowledge gained from these exercises must not be used to access, damage, or interfere with systems without permission.
The instructor, authors, and Networkwalks are not responsible for any misuse of the information presented in this report. All activities must comply with applicable cybersecurity laws and ethical hacking principles.
2. Introduction
This report documents two practical cybersecurity activities completed during my internship program at Networkwalks. The activities focused on the reconnaissance and footprinting phase of penetration testing using Google Hacking Database (GHDB) and Maltego.
The first practical involved using Google Hacking Database to identify publicly indexed information about a target through specially crafted Google search queries, commonly known as Google Dorks.
The second practical involved using Maltego to perform visual reconnaissance and gather publicly available information about a target. Maltego helps security professionals discover relationships between domains, IP addresses, email addresses, organizations, and other digital entities.
Both exercises demonstrate how cybersecurity professionals can gather and analyze publicly available information before proceeding to more advanced security assessment activities.
The practical exercises were performed within the authorized educational scope of the Networkwalks internship program.
3. Tools Used
The following tools were used during the practical exercises.
Tool	Purpose
Google Search Engine	Used to search for publicly indexed information.
Google Hacking Database (GHDB)	Provides Google Dork queries for identifying exposed information indexed by search engines.
Google Dorks	Used to perform targeted searches for publicly accessible information.
Maltego	Used for visual link analysis and gathering information about digital entities.
Kali Linux	Operating system used for cybersecurity and reconnaissance activities.
Internet Connection	Required to access online reconnaissance resources.
4. Activities Performed
4.1 Footprinting with Google Hacking Database (GHDB)
The first activity involved using the Google Hacking Database to understand how search engines can reveal publicly indexed information about websites and their digital infrastructure.
Google Hacking Database contains search queries that can help security professionals identify different types of information exposed through search engine indexing.
During this practical, I explored the use of Google Dorks to perform targeted searches and understand how publicly available information can be discovered.
The activity involved the following steps:
1.	Accessing the Google Hacking Database.
2.	Exploring different categories of Google Dorks.
3.	Identifying suitable search queries for the assigned practical.
4.	Executing authorized searches using Google Search.
5.	Observing the information returned by the search engine.
6.	Recording relevant findings for documentation.
Queries/Commands Used:
intitle:"webcamxp" "Flash JPEG Stream
intitle:index.of "parent directory" mathematics pdf
Observations and Findings:
I saw some open camears and was able to take down the ip.addr
Security Significance:
Google Hacking Database demonstrates that information intended to be publicly accessible can sometimes reveal more about an organization's digital environment than expected.
Exposed documents, directory listings, login pages, and other indexed resources may provide useful information to an attacker during the reconnaissance phase.
Organizations should therefore regularly review their publicly accessible resources and ensure that sensitive information is not unintentionally exposed through search engine indexing.
Evidence:
[INSERT GHDB SCREENSHOTS HERE]
4.2 Footprinting with Maltego
The second activity involved using Maltego to perform footprinting and visual reconnaissance.
Maltego is an open-source intelligence (OSINT) and link-analysis tool used to discover relationships between different digital entities.
It helps security professionals investigate a target by collecting publicly available information and presenting the relationships between discovered entities in a graphical format.
During this practical, I explored how Maltego can be used to investigate a target domain and identify related information.
The activity involved the following steps:
1.	Launching Maltego and accessing the working environment.
2.	Creating a new investigation graph.
3.	Selecting the appropriate starting entity, such as a domain.
4.	Entering the authorized target information.
5.	Running available transformations to discover related entities.
6.	Examining the relationships between discovered information.
7.	Analyzing and documenting the results.
Target Used:
Networkwalks.com
Transformations Performed:
ALL Transforms
Observations and Findings:
Found networkwalks linked with different email address
Security Significance:
Maltego demonstrates how different pieces of publicly available information can be connected to build a broader picture of an organization's digital footprint.
The relationships between domains, IP addresses, DNS records, and other entities may help security professionals understand the structure of an organization's online infrastructure.
This information can also help organizations identify unnecessary exposure and improve their overall security posture.

5. Risk Analysis / Impact
Based on the activities performed during the two footprinting exercises, the following potential security risks were considered.
#	Risk / Finding	Potential Impact	Risk Level
1	Sensitive information indexed by search engines	May expose information that should not be publicly accessible.	Medium
2	Publicly accessible directories or documents	May reveal organizational information and internal resources.	Medium
3	Exposed login pages identified through search queries	May help attackers identify authentication endpoints for further assessment.	Medium
4	Publicly discoverable domain information	May assist attackers in understanding an organization's online presence.	Low
5	Relationships between digital entities discovered through Maltego	May help attackers build a broader picture of the target infrastructure.	Medium
6	Excessive publicly available organizational information	May increase the amount of intelligence available to potential attackers.	Medium
Risk level key: Critical | High | Medium | Low
Note: The risks listed above represent potential security concerns associated with footprinting. They should not be interpreted as confirmed vulnerabilities unless supported by actual evidence from the practical exercises.
No exploitation or unauthorized access was performed as part of these activities.
6. Recommendations
Based on the concepts learned during these practical exercises, I recommend the following security improvements:
1.	Review publicly indexed information: Organizations should regularly check what information about their systems and services is available through search engines.
2.	Protect sensitive documents: Confidential documents should not be stored in publicly accessible directories.
3.	Configure web server permissions: Directory listings and unnecessary public file access should be disabled.
4.	Monitor digital footprints: Organizations should periodically review their online presence to identify unintended information exposure.
5.	Secure publicly accessible services: Login portals and other exposed services should have appropriate authentication and security controls.
6.	Perform regular OSINT assessments: Organizations should use reconnaissance tools to understand what information an external party can discover about them.
7.	Review domain and DNS information: Public DNS records and related infrastructure information should be maintained properly.
8.	Follow ethical hacking principles: All footprinting and reconnaissance activities must be conducted within an authorized scope.
7. Conclusion
During my cybersecurity internship program at Networkwalks, I completed practical activities covering footprinting using Google Hacking Database and Maltego.
Through the GHDB practical, I learned how Google Dorks can be used to discover publicly indexed information and understand the potential security implications of information exposed through search engines.
Through the Maltego practical, I learned how to investigate digital entities, perform transformations, discover relationships between different entities, and visualize information using a graphical link-analysis interface.
These exercises helped me understand the importance of reconnaissance in penetration testing and how publicly available information can provide valuable intelligence about an organization's digital environment.
I also learned that effective cybersecurity involves identifying potential information exposure before it can be used by malicious actors.
Overall, the practical exercises improved my understanding of OSINT, digital footprinting, information gathering, and the importance of documenting security observations.
8. Evidence Collected
8.1 Evidence – Footprinting with GHDB

Task1	Find 10x live vulnerable security camera links that are exposed & accessible from Internet. List them in below table along with their relevant dork that you have used.
No.	Link	Relevant Dork	Username /Password 
(if any)
1	http://122.116.41.8:8080/ 
intitle:"webcamXP" inurl:8080	---
2	http://109.233.191.130:8080/	intitle:"webcamxp" "Flash JPEG Stream"	
3	http://72.199.200.5:8080/	Intitle: “webcamXP 5”	
4	http://153.198.1.158:60001/	insecam.org/en/view/1012786/	
5	http://182.169.49.34:50003/	insecam.org/en/view/1012773/	
6	http://31.164.39.184:50000/	insecam.org/en/view/1012766/	
7	http://68.82.72.116:2006/	insecam.org/en/view/1012740/	
8	http://108.52.105.4:50002/	insecam.org/en/view/1012760/	
9	http://180.27.198.3/	  insecam.org/en/view/1012779/	
10	http://106.180.210.233/	insecam.org/en/view/1012770/	
11	http://203.135.192.190:8080/	  insecam.org/en/view/175/	


Task2	Find 10x listings which contain downloadable mathematics ebooks in PDF format:
No.	Link	Relevant Dork	Username /Password 
(if any)
1	https://www.skylineuniversity.ac.ae/pdf/math/ 
intitle:index.of "parent directory" mathematics pdf	---
2	http://erewhon.superkuh.com/library/Math/	intitle:index.of "parent directory" mathematics pdf	
3	https://mathflix.luc.edu/pdfs/Algebra/	intitle:index.of "parent directory" mathematics pdf	
4	https://netlib.org/math/docpdf/	intitle:index.of "parent directory" mathematics pdf	
5	https://www.fsr.ac.ma/DOC/cours/maths/	intitle:index.of "parent directory" mathematics pdf	
6	https://www.jsoftware.com/books/pdf/	intitle:index.of "parent directory" mathematics pdf	
7	https://math-olymp.rudn.ru/doc/	intitle:index.of "parent directory" mathematics pdf	
8	https://justmathbg.info/files/	intitle:index.of "parent directory" mathematics pdf	
9	https://ochicken.net/library/Mathematics/	intitle:index.of "parent directory" mathematics pdf	
10	http://inis.jinr.ru/sl/vol2/Mathematics/Math.Encyclopedia/Pdf/	intitle:index.of "parent directory" mathematics pdf	
11	https://education.giakonda.org.uk/Maths/	intitle:index.of "parent directory" mathematics pdf	

8.2 Evidence – Footprinting with Maltego
<img width="1355" height="699" alt="maltego-result1" src="https://github.com/user-attachments/assets/c983fb93-085a-4e3e-be9b-a59371e0bc6d" />
<img width="1366" height="718" alt="maltego-result 2" src="https://github.com/user-attachments/assets/7d9e5abe-e5db-453f-af09-bef0143bcbe9" />
<img width="1353" height="712" alt="maltego-result 3" src="https://github.com/user-attachments/assets/21aedb8a-2bd8-417e-99b0-06557faa4683" />
______________________________________
END OF REPORT
Author
Ibrahim Abimbola Bello
Cybersecurity Professional
Networkwalks – Cybersecurity Internship
Batch: B084
LinkedIn: https://www.linkedin.com/in/bello-ibrahim-a42995441/
________________________________________
Project Information
•	Program Name: Cybersecurity Program at Networkwalks
•	Week: 02
•	Practical Activities: Footprinting with GHDB and Footprinting with Maltego
•	Focus Area: Reconnaissance and OSINT
•	Repository: GitHub

