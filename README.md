# CS305
Module 8 Journal

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  The client was Artemis Financial, a financial service company that manages sensitive client information like investments, insurance, and retirement data. The company needed to make sure
  that its Java-based RESTful web application was secure, especially because it handled personal information and financial data. Artemis Financial wanted me to perform a vulnerability
  assessment to identify any weaknesses in their software and recommend secure coding practices.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

   When I ran the OWASP Dependency-Check and performed a manual code review, I thought I did well at identifying the out dated libraries and potential security risks such as unsafe dependencies
   in the Spring Framework, Jackson, and Tomcat. I explained the risks and provided specific version upgrades to fix them. Coding securely is very important because it protects the users data
   and makes sure that the system can be trusted by both the clients and the users. Secure software adds a lot of value to a company by reducing any risks of breaches, maintaining trust between
   their customers, and avoiding any costly legal fees or damage to their reputation.

3. Which part of the vulnerability assessment was challenging or helpful to you?

   The most challenging part of the vulnerability assessment for me was sorting through the large number of CVEs and having to decide which ones were actual vulnerabilities and which ones were false
   positives. It required carefully reading each CVE and having to understand how it applied to the code. This however was also very helpful because it taught me how to interpret a static analysis
   report correctly which will be valuable for any future software security tasks.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

   I increased layers of security by upgrading outdated dependencies, using strong encryption like AES/GCM/NoPadding, enabling secure HTTPS communication, and generating a self signed certificate.
   In the future, I would continue to use tools like the OWASP Dependency-Check to scan for vulnerabilities, and I would apply secure coding standards like the OWASP Secure Coding Practices Guide
   to use the best mitigation techniques.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

   After refactoring the code, I made sure that the software still worked correctly by testing it through Eclipse to confirm that all the REST endpoints returned the correct data. I also
   did a secondary dependency scan to make sure that refactoring did not introduce any new vulnerabilities.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

   The main tools and resources I used was the OWASP Dependency-Check Maven plugin, Java Keytool, and the textbook Iron-Clad Java by Jim Manico and August Detlefsen. These helped me to understand secure
   coding principles such as encryption and self signed certificates. I also followed the best practices from the OWASP Secure Coding Practices Guide. These tools will be very helpful for
   future assignments whenever I need to analyze software for security risks or build a secure application.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

   For future employers, I could show Project One and Two as an example of my ability to perform a complete software security assessment. It demonstrates skills in static testing, code
   review, vulnerability analysis, secure coding, and implementation of encryption and certificates. The projects show that I can identify security issues and verify functionality
   afterward. 
   
