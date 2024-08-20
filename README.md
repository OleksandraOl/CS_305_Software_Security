# CS_305

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial is a consulting company that develops financial plans for their customers. Since the company deals with a lot of personal information, including bank accounts, secure communication is a crucial part of its operations. Cloud computing will mitigate the need to manage servers and focus on the application itself. The API clients should be secured. Constant library monitoring and updating will ensure smooth work and enhanced security. 
  
2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?   

   I did well in developing the hash function and running dependency checks. I also established the secure connection by generating a self-signed certificate of authority. Using cybersecurity best practices mitigates the risks of possible attacks, protects sensitive data, boosts the company's reputation, and attracts more clients by presenting itself as a trustworthy business. This also reduces the cost of dealing with possible future attacks by addressing them early in the software development life cycle.

3. Which part of the vulnerability assessment was challenging or helpful to you?

   The most challenging part of the vulnerability assessment was identifying false positive dependency vulnerabilities, as this required knowledge of the whole application architecture.
   
4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

    Implementing the hash function, establishing a secure connection using a generated certificate of authority, and running dependency checks increased the layers of security. In the future, to assess vulnerabilities, I would do a manual code review, run OWASP Dependency Check, and test the code by inputting different data. The mitigation techniques will depend on the type of vulnerabilities and risk level.
   
5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

    I regularly checked the code after refactoring for any warnings. I also ran additional dependency-check reports to see if new vulnerabilities appeared. I refactored code in small iterations, understanding the problem, designing, implementing, and testing. This approach helped me incorporate best industry practices.
   
6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  From my standpoint, the most helpful tool that I will use in future assignments is the OWASP Dependency Check tool. Implementing secure code practices should start in the early stages of SDLC. I would make sure to implement security at the early stages of developing code.
    
7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
   
   There are many things that I might show future employers from this assignment. First of all, there are written assignments that prove the understanding of the basic concepts of secure coding. The implemented hash function is one of the steps to a secure application. I would also show the self-generated certificate of authority and implemented secure connection based on the certificate. 
