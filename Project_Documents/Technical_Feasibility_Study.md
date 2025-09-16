[README](../README.md)

# Technical Feasibility Study
## Technology Stack Evaluation
In terms of experience, I have years of general programming experience and knowledge of programming concepts, with applying said knowledge; using industry tools like the professionals do
The DJango, React, PostgreSQL technology stack is the stack I have chosen to learn, so above all this is why I am using them in this project, but.
### DJango
DJangos app based methedology allows me to seperate the product into seperate apps first and foremost. And second it proves a lot of features built in which help speed up development and enhanse security as their prebuilt apps are tried and tested. For my project hyper efficient processes aren't required so DJango (running on Python), provides enough efficiency.
### React
React the front end framework allows me to easily and quickly build and configure components to build my web pages.
### PostgreSQL
It is not as lightweight as SQLite, but is more commonly used in the industry and provides the scalability SQLite doesn't. (And this will help develop at least a novice level understanding of implementing PostgreSQL)
### Web Server
I have no experience configuring and setting up any web servers, though once I have a functional front and back end I will research and choose an appropriate one to setup the front and backend, along with configuring filtering and routing and whatnot.
## Skill Assessment
I have a solid general programming knowledge and programming conceptual knowledge, but for this project:
- Novice knowledge of DJango - practiced with django for a while, understand most of it, though some features may take a bit longer.
- Beginner knowledge of React - practiced with react for a while, I understand a good portion of it, though some more complex concepts may need to be researched to learn.
- PostgreSQL knowledge - I understand conceptually all the concepts in SQL, I have limited experience with SQLite, though I believe it will not take long to pick up PostgreSQL.
- General Professional Documentation - I generally understand this conceptually, but I have limited experience producing professional grade documentation, as one of my tasks I will try and ensure everything is to a professional standard.
- Limited Testing Experience - I understand the testing required but I have limited experience in the implementation of testing, I will expect some time is needed to ensure everything runs smoothly.
I have a pretty decent but still quite beginner understanding of DJango meaning some more complex concepts may take longer than planned.
React I am newer with, I do understand its core but the complexities of integrating with DJango may take some time.
- 
## Resource Availability
I will try and make this website for free, I have all the tools I need, git, visual studio code, websites like draw.io for diagramming, and whatever tools I may require. + my MiniPC
## Hosting and Scalability
The hosting will be done on my local PC for smaller unit testing and if i wish to simulate internet traffic, my MiniPC (which is not physically connected meaning traffic would go through a wireless network (my WiFi)) (my internet speed is about 70 mbps so heavy load testing will have to consider this)
## Risk Analysis:
### Exceeding Deadline:
Given the tight constraints and quality requirements they is significant risk of going over the deadline, therefore a MVP will be developed, tested and debugged first and THEN only if they is enough time to do all that again + with the new feature, additional lower priority features will be added.
While performance is important, in cases like this, performance usually takes a back seat because modern computers are just fast enough to do stuff slightly less efficiently if you can get it working in 1/5th the time.
### Bugs:
Bugs will happen no matter how robust the testing. So in response I will.
- Have error handling in case anything fails so one bug doesn't break everything.
- Ensure thorough: unit testing, integration testing, system testing, acceptance testing and performance testing is done. (Given restricted time Security Testing in this case is a low priority, in a real deployment enviroment this is none negotiable). Without testing it goes from - a few bugs to - broken.
- Recognise no matter what you do, bugs will occur and things will break so it must be designed accordingly.
### Performance Issues:
Because the social media website is simple in its functionality and postgreSQL is performant with database quries, I expect performance to not be a problem, but still of medium priority I will perform performance testing.
### Security Risks:
If deployed to the internet they is the risk of security breaches and attacks, to prevent this:
- Passwords will be hashed (should store on seperate database but the project scope is too small, though django handles password hashing).
- Peeking Sensitive Information: - to prevent this any none public communication will be encrypted (may or may not implement this given time constraints)
- SQL Injections: DJango calls the database through functions eliminating the risk.
- CSRF Attacks: More sophisticated attack but as DJango offers CSRF tokens easily, I will use CSRF tokens to prevent such an attack.
- User Doxing: It is on the user to not dox themselves with public information, it is our responsibility to ensure sensitive information they set to private is securely stored. Private information will be encrypted (may or may not have time to implement this).

#### Contributors
- [Charlie Allen](./Contributors/Charlie_Allen.md)