## Project #3 CI/CD Project
[Link to the repo](https://github.com/alejandro-baez/Campus-and-Enrollment)
### **Overview**

The Campus and Enrollment project was originally a project I developed before my time at Multiverse. By the time I came back to this project over a year and a half had passed. This project was reused for the end of the deployment module. I decided to implement CI/CD through github actions as well as deploy my project through render and trigger a redeploy everytime a change is committed to github. Not only was I able to demonstrate my newly gained knowledge of CI/CD but this also allowed me to showcase my debugging skills as my application wouldn’t run after being outdated for not touching it in almost 2 years. 

### Hosted on Render
<img width="649" alt="MV-RENDER" src="https://github.com/user-attachments/assets/113d183e-c905-4427-b409-4ba84958bd48">

### CI/CD Implementation
<img width="1207" alt="MV-CI-CD" src="https://github.com/user-attachments/assets/39d53864-cb5d-42a4-9b51-428ac824d16c">

**What are the users?**
The primary users of the application are individuals who are seeking to integrate CI/CD to their application and use my application as a learning example. The original purpose of the application was to serve as a backend and frontend service for students and campuses. 

**What job does it form for them?**
The CI/CD portion of this application adds a layer of safety to the overall application that ensures that any changes that are pushed to the repository don’t break the application and stop it from redeploying automatically.  As a programmer, having this tool that catches any errors before an application is redeploying is an immense help

**What inspired you to make it?**
I decided to choose this project to implement CI/CD due to the complexity of this project. This is a full stack application with a complete backend and frontend along with a Postgres database. This mimics the large scale applications that software engineers are working with on a day to day basis

**What features are the most important?**
The most crucial feature of the application is the build_test_react.yml file that contains the bulk of the CI/CD feature. This file breaks down exactly what services are being run and what features are triggered when a commit gets pushed to the repository. 

### **STAR Interview**:

S- The situation was to independently design and build a full-stack application that synthesizes all the frontend, backend, and deployment skills that were learned thus far. Since the focus of the module was about deployment and CI/CD, we were allowed to choose an old project to integrate these new features.

T- After looking through various old projects, I landed on the Campus and Enrollment project from years ago. I knew that it was outdated since almost two years had passed but decided that it would be a fun challenge to not only make this project functional again but be able to add even more features to a project that I created when I first began my programming journey.

A- Due to the project being outdated, I had to update the connections and permissions to Postgres. This required reading up on the Sequelize documentation and implementing a new updated connection. I also ended up incorporating CI/CD integration and was able to successfully deploy this application on Render.

R- As a result I was able to revive a project that I had considered obsolete and outdated. With a new connection to the database, I was able to properly seed the database. The addition of CI/CD ensures that any new changes to the application are working properly before they are merged. With these added features, I have plans to update the front end to create a modern application. 



## Technologies
- React 18
- JavaScript
- Node v14
- Git and Github
- Github Actions
- Render


## Competencies
### JF 1.7 Can follow company, team or client approaches to continuous integration, version and source control

The main focus of this project was to focus on continuous integration. I was able to successfully complete this using github actions through a .yml file. Whenever a change to the app is pushed, the app is reseeded and is checked for any errors. Moving forward, this will be a great asset as I work on the front end of this project.


### JF 4.3 Is able to build, manage and deploy code into the relevant environment

This project allowed me to dive into render.  I had seen it used to deploy applications in past group projects, but this was the first time that I got to use it on my own. The process was fairly straightforward and it allowed me to deploy my project without any issues. I was able to connect to github pages which allowed me to integrate CI/CD. 

### JF 6.6 Shows initiative for solving problems within their own remit, being resourceful when faced with a problem to solve

Due to this project being old, I ran into a lot of issues and the biggest one happened as soon as I ran the app for the first time after almost two years. Immediately, no information appeared on the front end and I quickly realized that the connection with the Postgres database was no longer working through Sequelize. This meant that I had to read the updated documentation and pass the correct credentials to fix the issue.
