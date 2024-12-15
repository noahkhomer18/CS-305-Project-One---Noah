# CS-305-Project-One---Noah
Project one for software security course by Noah Khomer 
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial consulting company. The main purpose of this company is to provide financial planning services. One of the things that were required for this project was a security assessment of their web-based software. The purpose was to identify different types of vulnerabilities that are there so that we can fix them. Fixing these vulnerabilities would lead to compliance with different types of regulations like PCI DSS, GDPR CCPA and so many more others. The main purpose was to make sure that if there is any type of weakness next such as input validation, not secured communication or even outdated libraries so that we can modernize them and protect client information.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
One of the things I did perfectly was making sure all the input validation gaps are covered. I made sure that all the hardcoded credentials go in the env file and any type of missing https enforcement is applied. 

Which part of the vulnerability assessment was challenging or helpful to you?
One of the main challenges I had when building this project was to make sure that every single code was reviewed manually for any type of vulnerabilities. Tools like dependency check were very helpful for this, especially with a lot of outdated libraries, however there was still a big mix of like manual processing.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I was able to increase the security and apply layers of security by implementing different types of input validation. I made sure all the data is encrypted I made sure all the HTTPS can be enforced and lastly, I also make sure that the API calls are secure. Furthermore, I focused on updating any type of outdated dependencies because that automatically fixes a lot of issues. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
For the future plan I intend to use tools like static application security testing which can automate the vulnerability scanners so that all the compliance checklists can happen right away and this way I can only focus on mitigating the risk

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
To ensure that the code remain functional and secure I did not touch it for this project what I did was manually reviewed the project to make sure that there are no other type of underbellies for the main vulnerabilities that were there I did implement fixes and suggested what can be fixed in order to mitigate the risk

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
For this project, one of the main things I want to show my employers is that I can identify, assess and mitigate different types of security vulnerabilities. It can be noted that there are a lot of different types of software’s that can automate this process but knowing how to do it manually is still important. This way, I'm demonstrating my ability to read and understand different types of code to implement what is happening. Through this I was able to implement the compliance standards and use my ability to enhance the application security
