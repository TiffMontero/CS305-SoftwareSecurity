# CS305-SoftwareSecurity

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company that creates custom plans for their customers. This includes retirement plans, savings, and insurance, among others. They are looking to update their software, with a focus on their security.


### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I felt I applied static testing very well in order to help identify vulnerabilities in the client's software. Coding securely is crucial to prevent attacks and theft of information. This helps protect both the client and their consumers, which in turn solidifies the client's reputation.

### What part of the vulnerability assessment was challenging or helpful to you?**
Understanding the dependency check was challenging in the beginning, as I did not have prior experience with pom.xml files. 

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The biggest concern with this client was a lack of encryption. In response, I implemented a hash function, SHA-256 to be specific, in order to increase their software's security. In the future, utilizing the Dependency Check will be extremely helpful to identify where security improvements can be made.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Ensuring there were no errors in the code was crucial to the software being deemed functional and secure. This included additional testing and running another dependency check as needed.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Using source tools from Oracle along with OWASP Dependency Check and the NVD. I also did extensive research online when additional errors appeared. 

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I felt my ability to research, learn, and then explain/recommend vulnerabilities to a non-technical audience is a strong point. It can be easy to get caught up in regurgitating technical terms to a client, which will in turn cause more confusion. Explaining in a way that makes it both approachable without oversimplifying will help the client feel they know what services are being provided, which in turn will increase their confidence in you.
