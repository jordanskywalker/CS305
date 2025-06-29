# CS305

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
- For this project, the client was Artemis Financial. They needed help making sure their software was secure, especially since they deal with sensitive financial information. The goal was to figure out where their vulnerabilities were and fix them so their systems would be better protected.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
- One thing I think I did well was identifying and fixing the security issues I found. It helped me see how important it is to write code with security in mind from the beginning. When software is secure, it protects the company, its users, and its reputation.

3. Which part of the vulnerability assessment was challenging or helpful to you?
- One of the harder parts was making sure my vulnerability report was clear and thorough. I had to go through different logs and test a few different setups before everything worked right. Making the checksum feature run correctly and getting the SSL certificate working on port 8443 took some extra time and troubleshooting.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
- To boost security, I used SHA-256 for hashing and made sure all input was handled safely. If I were doing this again or working on something similar, I would keep using tools like OWASP’s top 10 and add even more security checks during development. It's better to catch issues early than fix them later.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
- After updating the code, I tested it to make sure it still worked the way it was supposed to. I double-checked the server responses, made sure the port and certificate were working, and took screenshots to show it was all running without errors.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
- Some tools and resources that helped were the OWASP guide, Oracle’s secure coding tips, and the Maven dependency checker. Those made it easier to make smart decisions while cleaning up the code. I also used screenshots and other references to back up the final report.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
- This project helped show what I’ve learned this term. It gave me a chance to apply real-world security practices, work with certificates, and clean up a codebase to make it safer. It’s something I’d feel good about showing an employer if they asked about my experience with secure software.
