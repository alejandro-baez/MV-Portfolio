## Project #2 HackaThon
### **Overview**

For my Multiverse HackAThon, I decided to focus on a topic that was music related. This was due to my parent company being Warner Music Group, a record label company. In wanting to understand the cross section of music and software engineering, I decided to focus on Spotify’s API to create my own API using Python’s Flask framework to return and store artist information in a Postgres database.  At the time of participating in the HackaThon, I had just learned Python and wanted to bring together my different interests to create a functional application.

**What are the users?**
The primary users of the application are software engineers who would like to access Spotify’s API in a simpler and more direct way. The reason for this is that Spotify’s token authorization expires after a certain time, this can get in the way of developing a program as one has to constantly refresh and retrieve a new token to continue being able to access Spotifty’s information. My application solves that problem by using Python’s apscheduler library to create a scheduler that refreshes this token after a certain time, ensuring that not a second goes by without having a working token.

**What job does it form for them?**
This particular app does two important jobs for the users. The first is that it allows a user to continually access Spotify’s API without interruptions by sending a working token on a scheduled time. The second is that it simplifies how users actually interact with Spotify itself. As it currently stands, the Spotify API is convoluted in querying information. I had to read outdated Spotify documents to understand how to query artist and song data. In hopes of trying to make  a more direct API, I molded the current Spotify search feature so that you only had to submit the name of what you’re searching for and whether it’s a song, album or artist to return the correct information.

**What inspired you to make it?**
I created this app due to my interest in music and wanting to further explore the connections between music and technology. This application was developed before I began working at Warner Music Group therefore my knowledge about how art and technology can be connected was limited. Not only was I able to apply my newly gained knowledge of Python but also learned about the music industry at the same time

**What features are the most important?**
The most important parts of this application are Spotify’s API, Python’s Flask framework, and the token scheduler. All these parts work together and if one section fails, the entire application fails. The token scheduler ensures that a valid token is present at all times, allowing us to access Spotify’s API. Flask is then used to access and query information from Spotify in a much more direct way by only needing to submit an artist’s name or album to then retrieve and store the information in a Postgres database


### **STAR Interview**:

S- After completing a 3 month bc with Multiverse, we were tasked with learning more about the company's tech stack and to develop a project that we could showcase to our managers and team members. This project would reflect the knowledge we acquired during bc and during the time we had to self study.

T- This was a project where everything was designed by myself, from the idea to the execution. This project came after we worked on a group project where everything was divided evenly so the approach was drastically different. I knew I wanted to make the project music related in order to emulate what I would be doing at WMG. I also wanted to showcase my newly gained Python skills and connect it with Postgres, something that I’ve done multiple times with Javascript.

A- I ended up looking at multiple different music API’s that I could use to incorporate into my application, and I ultimately decided on Spotify’s API since it was easily accessible, free, and I noticed some difficulties when trying to query specific data.  These difficulties inspired me to debug and make this process much easier. I also researched various Python libraries that could help me fix the token issue and was pleasantly surprised to find out about apscheduler and since this was something that I had never used before, I watched numerous videos and read up on its documentation.

R- As a result I was able to fix the glaring token issues by running a schedule and refreshing the auth token with a working one every 59 minutes. I also used Flask to create my own API that solves some of Spotify’s querying issues. 

## Technologies
- Python 3.7
- Spotfiy API
- Flask
- Git and Github
- APScheduler
- Psycopg 2.9


## Competencies
### JF 3.4 Can create a logical and maintainable codebase

I was very mindful of maintaining a clean and organized codebase. I separated my files depending on what purpose they served. For example, I had a file only reserved for authenticating and generating the spotify api and then imported that into my main file that actually implemented this feature. I also had a separate file that stored my client id and secret code that allowed me to access Spotify’s API. 


### JF 5.5 Understands and can apply structured techniques to problem solving, can debug code and can understand the structure of programmes to identify and resolve issues

A large part of this project revolved around debugging. Since my Python journey was just beginning at this point, there were times where either my Flask API wasn’t working properly or the information wouldn’t get sent to the database, and I had to debug the issue. I would first identify where the issue was coming from through error legs and run different print statements to verify.


### JF 6.4 Works independently and takes responsibility. For example, has a disciplined and responsible approach to risk, and stays motivated and committed when facing challenges

This entire project was worked on independently. I allocated time to research different frameworks and Python libraries to suit my needs. I remember specifically, having a difficult time implementing apscheduler into my project as I need it to communicate through different files. A large portion of this application depended on having a working token at all times so I had to stay committed to figuring out a solution as to why the scheduler wasn’t working as expected. Eventually, after watching various tutorials, reading on the documentation, and not giving up, I was able to get it fully functioning.

