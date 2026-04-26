# CS-305-Software-Security
Course work from SNHU CS-305 class. 

## Questions

#### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that needed help improving the security of its software application. The main issue was protecting sensitive financial data and ensuring secure communication between the client and server. The goal was to identify vulnerabilities and refactor the application to follow secure coding practices, including encryption, hashing, and HTTPS implementation.

#### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I did well in identifying weak areas in the application, especially around data transmission and lack of integrity verification. I focused on adding hashing and securing communication, which directly addressed those risks. Coding securely is important because it prevents data breaches, protects user information, and ensures systems cannot be easily exploited. Strong software security adds value to a company by building trust with users, avoiding financial loss, and maintaining a reliable reputation.

#### Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was configuring the HTTPS setup and keystore correctly, since even small mistakes caused the server to fail. However, this was also the most helpful part because it gave me a better understanding of how secure communication actually works behind the scenes.

#### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by adding SHA-256 hashing for data integrity and configuring HTTPS using a self-signed certificate to encrypt data in transit. I also reviewed the code for logic errors and ensured proper structure. In the future, I would continue using tools like dependency-check, static analysis tools, and manual code reviews to identify vulnerabilities and decide on the best mitigation techniques.

#### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure the application was both functional and secure, I tested the code after each change and verified that the application ran without errors. I used the /hash endpoint to confirm the checksum worked correctly and accessed the application through https://localhost:8443/hash to verify secure communication. After refactoring, I ran dependency-check again to ensure no new vulnerabilities were introduced.

#### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used Java’s built-in security libraries for hashing, the keytool utility for certificate generation, and the OWASP dependency-check tool for vulnerability scanning. I also relied on debugging, testing, and reviewing logs to fix issues. These tools and practices will be useful for future projects involving secure development.

#### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?


