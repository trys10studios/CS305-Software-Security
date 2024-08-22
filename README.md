# CS305 Software Security

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client?**
Artemis Financial is a consulting company specializing in creating personalized financial plans, including savings, retirement, investments, and insurance. They sought to develop a secure web application to protect their global customer base and enhance their online services. 

**What issue did the company want you to address?**
Artemis Financial sought to modernize their software to reach global users and needed a secure, client-facing website to support this expansion. They were already utilizing RESTful APIs for their web application but wanted to ensure these APIs were as secure as possible to protect their clients' data and maintain trust. My role was to enhance the security of their application while supporting their growth goals and global reach. 

**What did you do well when you found your client’s software security vulnerabilities?**
I successfully identified and mitigated most of Artemis Finacial's software vulnerabilities by updating dependencies to their latest versions, ensuring the application was shielded from known exploits. Additionally, I implemented secure practices like utilizing SHA-256 for hashing algorithms and RSA for key encryption. These measures reinforced the software’s integrity and protected sensitive data, demonstrating my ability to apply strong cryptographic techniques and maintain the system’s security posture.

**Why is it important to code securely?**
Secure coding is paramount because it prevents introducing vulnerabilities that could be exploited by attackers. Unsecure code can lead to data breaches, loss of sensitive information, financial damage, and a loss of trust with users. By adhering to secure coding practices, you minimize risks, protect user data, and ensure the stability and integrity of your software. In today’s environment, where cyber threats are constantly evolving, secure coding is essential to building resilient systems that stand up against both known and emerging threats. 

**What value does software security add to a company’s overall well-being?**
Strong software security is crucial for a company’s overall well-being because it protects its assets, reputation, and long-term viability. When vulnerabilities are addressed from the start, it builds a foundation of trust with customers, stakeholders, and partners. A well-secured system reduces the risk of breaches, minimizes potential financial losses, and ensures regulatory compliance. Additionally, consistent security practices enable smoother operations and scalability by reducing the likelihood of disruptions. Ultimately, robust software security safeguards both the company’s future and the trust it’s built with its clients. 

**Which part of the vulnerability assessment was challenging or helpful to you?**
The most challenging part of the vulnerability testing was perusing through hundreds of vulnerabilities and reading about them. However, this was also a great learning experience, as it revealed what these applications and dependencies do. I have become more comfortable using Maven as a dependency-checking tool and have gained a deeper awareness of vulnerabilities in dependencies, not just in the code I wrote myself. 

**How did you increase layers of security?**
I increased layers of security by implementing a multi-pronged approach. This included updating outdated dependencies to mitigate known vulnerabilities, using SHA-256 for secure hashing, and implementing RSA encryption for key management. Additionally, I ensured that the RESTful APIs had secure authentication mechanisms, including data encryption during transmission. These combined measures helped create a more secure environment by addressing multiple potential attack vectors. 

**In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
While tools like Maven are valuable for detecting vulnerabilities, relying solely on them is insufficient. In addition to automated tools, I would conduct manual code reviews to identify logic bugs that could introduce attack vectors. This approach includes analyzing how data flows through the application and ensuring that security controls are applied consistently. Depending on the context, I’d also consider penetration testing, static analysis tools, and threat modeling to fully understand potential risks and select the best mitigation techniques. 

**How did you make certain the code and software application were functional and secure?**
I ensured the code and software application were both functional and secure by adhering to industry best practices. This included writing clean, well-documented code, removing any unused or dead code that could be exploited, and maintaining clear comments for future developers. I also performed thorough testing to confirm that security measures were effective and did not compromise functionality. By balancing best practices with diligent testing and code hygiene, I could deliver a secure and reliable application. 

**After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
After refactoring the code, I reviewed any new dependencies through Maven to check for potential security issues. Additionally, I carefully evaluated class visibility to ensure only the necessary classes were publicly accessible, reducing the attack surface. Although input sanitation was not a major concern in this project, I am prepared to validate and sanitize input when needed to prevent injection attacks or other input-based vulnerabilities.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
For my work with Artemis Financial, I used Maven for dependency checks, the Spring Boot Framework, and several industry-standard coding practices. These tools ensure both security and maintainability. I also used Java libraries, which are still highly relevant for legacy Android applications, standalone programs, and even modern applications. Given the continued importance of Java in the industry, these skills and tools are valuable assets for future assignments. 

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
From this assignment, I would highlight my attention to detail and commitment to secure coding practices. This includes highlighting how I ensured code quality through good commenting and clear documentation. I would also show my approach to mitigating threats by updating dependency versions to address security vulnerabilities. These aspects reflect my ability to maintain a secure and well-maintained codebase, which is crucial for any software development role. 

 
