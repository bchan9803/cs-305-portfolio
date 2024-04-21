# CS 305 Portfolio
### Bryan Chan, 2024



## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that engages in financial work with a wide range of clients. In order for their business to continue thriving, they require a modern software that utilizes the latest security features. In addition, they want to incorporate authenticity checks and encryption to their web interface which is open to the public. These measures can increase the overall security of the interface.

## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
After working on the client’s program, I demonstrated proficiency in adding encryption, which the program lacked. This is important to code security, as un-encrypted data can be accessed by attackers who can abuse the data. This adds a great value in the security of the company’s software, since un-encrypted data—-especially in the context of a financial company—-can protect the user’s sensitive data from being stolen.

## What part of the vulnerability assessment was challenging or helpful to you?
The “cryptography” portion of the vulnerability assessment was helpful, since it details the importance of encrypting incoming data for the protection of the user.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
In addition to encryption, I implemented authenticity to the client’s program by exporting a self-signed certificate to the program. For future projects, I intend to utilize the dependency-check report from OWASP, since it shows every potential vulnerabilities in the program. A helpful mitigation technique for dealing with vulnerabilities would be to update the program's dependencies since outdated code can lead to security problems.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I conducted a static testing of the program to ensure that no new vulnerabilities were added to the program. Additional testing of the program ensures that it will remain functional and secure.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Adding encryption and authenticity to the program will be helpful for future projects, since they ensure that the software will be safe from data breaches and fraudulent identities. 

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
In the context of this project, I will emphasize the cryptographic portion of the program, since it demonstrates thoughtful and intentional security knowledge, which will be helpful to employers.
