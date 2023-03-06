

## Fully responsive single page application made using MERN Stack! :blue_heart:

### TECH USED
  -   React
  -   Node
  -   Mongo db
  -   Express
  -   Redux
  -   Redis
  -   Jest

## DATABASE USED
  - Mongo
  - Redis

---

## Getting Started

Clone the repo to your local environment, you have to seperately install all the dependencies for backend and frontend. 

For Backend, go to the backend folder (cd Backend) and run 
``` npm i ```

  - Install [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)
  - or, you can use the [website](https://account.mongodb.com/account/login) 
  
  - add your environmental variables
  - Create a .env file in the root directory of the backend folder and add your tokens there with respect to the config files variables.
 
    - ACCESS_TOKEN_SECRET = "some secret"
    - ACCESS_TOKEN_LIFE = time
    - REFRESH_TOKEN_SECRET = "some secret"
    - REFRESH_TOKEN_LIFE = time
    - SENDGRID_KEY = ""
    - MONGO_DATABASE = ""
    - OAuth2Client = ""
    - STRIPE_SECRET_TOKEN = ""
    - REDIS_HOST = ""
    - REDIS_PASSWORD = "" 
    - REDIS_PORT = ""

  ### Note: Make sure the .env files variables matches with that of the config files like the image below.
  
  ![env files variables](https://raw.githubusercontent.com/ayush-lab/Coursera-Clone/main/Front-end/src/assets/env%20variables.png)


For Frontend, go to the frontend folder (cd Front-end) and run
``` npm i ```


To run a development environment, you can use the `npm start` command. This will start up a development web server on port 3000 for frontend, and a nodemon-watched API server on port 8080.

Note: you have to do npm start for backend and frontend seperately.

## Unit testing

You can test the backend, express endpoints using command ( npm test )
    
## Docker Compose

  Coursera Clone is dockerised and docker hub repository can be found here https://hub.docker.com/repository/docker/ayushverma/coursera/general

  If you use Docker and Docker Compose, you can start the entire project with:

  ```
  docker-compose up
  ```
---

## 🏭 Features

#### Student
- [x] **Authentication system** with signup,login,otp verification,resend otp,forgot password (fully validated with bootstrap alerts)
- [x] **Google authentication (Oauth2)** using react-google-login and google auth-library
- [x] **Stripe Payment** gateway integrated with backend to buy courses
- [x] **Redux store** to easily manage states
- [x] Homepage with courses being fetched categorically
- [x] **Recommended Courses** based on user's preferences
- [x] **Rating** of Courses
- [x] **Bookmarked** Courses where users can remove or add bookmark
- [x] Download **resourses** (pdf - notes)
- [x] Responsive React Video player for videos
- [x] Progress bar 
- [x] CoursePage with all the content of the course
- [x] **Searching** based on course and teacher
- [x] **Real Time Live Group classes**

#### Teacher
- [x] Proper Authentication system with signup,login,otp verification,resend otp,forgot password (fully validated with bootstrap alerts)
- [x] Fully validated teacher uploading form with descriptition,title,Image and other details
- [x] CkEditor for writing in textbox with abilities to add diffrent headings,paragraphs,bold,italics,link,tables,sizes etc
- [x] Teacher can upload upto 5 videos with upload bar to show progress
- [x] Teacher can see their uploaded courses
- [x] Teacher can delete their course
- [x] Teacher can edit their course


---
### Responsive Designs
#### Mobile Design Authentication
![alt text](https://raw.githubusercontent.com/ayush-lab/Coursera-Clone/main/Front-end/src/assets/mobileLogin.png)

 
#### Mobile Design CoursePage
![alt text](https://raw.githubusercontent.com/ayush-lab/Coursera-Clone/main/Front-end/src/assets/mobilecourse.png)






