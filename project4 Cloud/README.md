## Project #4 Cloud Elective Project
[Link to the repo](https://github.com/alejandro-baez/amplify-cognito-trivia)
### **Overview**

I built the Move Trivia web application during the Cloud Elective Hackathon project using React to create the front end portion, AWS Cognito for the signup and login, and AWS Amplify for deployment. The app first leads users to a login/signup page and are then allowed to participate in a 9 question movie trivia game where the score is displayed at the end.

### Hosted on Amplify
<img width="664" alt="MV-Amplify" src="https://github.com/user-attachments/assets/e7ba0565-136d-4b6f-bbe8-bfa2c503c986">

### Cognito User Pool Feature 
<img width="484" alt="MV-USER-POOL" src="https://github.com/user-attachments/assets/662af5f2-30ad-4294-b532-3c7b96957440">

### SignUp Page
<img width="474" alt="MV-Signup" src="https://github.com/user-attachments/assets/ee638389-9311-458b-b925-f9f61266d641">

**What are the users?**
The users of the Movie Trivia app are individuals who are movie fanatics and want to put their movie knowledge to the test. It can also be for the regular movie enjoyer who wants to expand their movie horizons


**What job does it form for them?**
This particular app acts as a quiz for users, in hopes that users will learn one or two new movie facts or even be inspired to watch a new movie that they find listed as one of the answers.

**What inspired you to make it?**
I’m a huge movie fan. I love all kinds of movies but honestly, I feel like I haven’t watched as many movies as I used to. I took this as an opportunity to rekindle that love I have for movies by searching up movie trivia and testing myself to see what I knew and what I had to learn. I also deal with authorization at work and wanted to research different ways of incorporating this to a project.

**What features are the most important?**
The two most important features are the ones relating to the AWS feature, Cognito and Amplify. These are two features that I have never dealt with before but found extremely interesting once I learned about them. The concept of AWS Cognito creating user pools that are used to authenticate a user without having to develop a backend let me know that I had to try it out. I was able to completely set up Cognito and its corresponding settings through its command line feature and that allowed me to incorporate Cognito much easier. AWS Amplify then allowed me to deploy and integrate CI/CD to my application

### **STAR Interview**:

S- The main purpose of this project was to showcase our abilities after spending some time learning about the Cloud and AWS’s many features. Even though I have worked with AWS at WMG, I haven’t really implemented AWS into a project from scratch. In that sense, this was a new experience for me.

T- I wanted to create a simple project since the focus was on incorporating AWS to my project. Due to this I wanted to create something that was fun and interesting for me but also had a purpose. I was also initially overwhelmed about what specific AWS to focus on, since there’s a seemingly endless amount. 

A- Due to my initial tasks, I decided to create an application related to movies. The reason for this is because I’m a huge movie lover. I wanted to create something light hearted and interesting for myself. After watching various videos and reading up on AWS’s features, I decided on Cognito and Amplify. The reason for this is because at WMG and pretty much anywhere, authentication and authorization are extremely important and I wanted to be able to gain more insight about how this works by implementing Cognitio. I also wanted to explore other ways to deploy an application , other than Render.

R- As a result, I was able to have a working trivia game that allows users to sign up, login, deployable and can be accessed through a link. This project deepened my understanding in AWS and allowed me to explore my interests while teaching me new methods to connect features that I already know how to deal with such as auth and deployment. 


## Technologies
- React 18
- JavaScript
- Node v14
- Git and Github
- AWS Amplify
- AWS Cognito
- Flexbox


## Competencies
### JF 1.6 Can follow software designs and functional/technical specifications

I  designed the idea of developing a  movie trivia app for this Cloud Project and decided to incorporate AWS Cognito and Amplify after doing some research. I read through both documentations and was able to connect Cognito to my application via the command line. This allowed me to not depend on the AWS user interface hub, something that I also try to avoid when working at WMG. 


### JF 2.3 Can develop effective user interfaces

Although the main focus of the project wasn’t the front end user interface, I still dedicated a good portion of my time creating an organized and working front end. I had color to my application and I implemented button features that were evenly spaced out using flexbox. At the end of the day, I wanted a working application that was worthy of implementing cloud features. 


### JF 3.7 Can implement authentication and authorization to an API. 

Using AWS Cognito and its command line feature, I was able to successfully create a user pool in AWS that keeps track of all current and new users. This allows me to view who is accessing my application and even verifies a user through an email that is sent when someone initially creates an account.

