
# Boomer - SocialMedia App
-> This MERN app is a responsive web application with authentication, like functionality, and dark mode
support. It leverages Material-UI (MUI) for a modern UI design.  
-> Users can register, post, login, and logout securely using JSON Web Tokens (JWT). They can also like and dislike content, with the number of likes displayed.  
-> The app offers a mobile-first design, powered by MongoDB for data storage and Express.js for the backend
API.
## Live Demo
https://socialmedia-boomer.netlify.app/



## Screenshots
![Screenshot (41)](https://github.com/ankittbisht/SocialMediaApp-Boomer-/assets/110447589/01ae081f-6e96-415f-ab0c-cb66a393041f)  

![Screenshot (43)](https://github.com/ankittbisht/SocialMediaApp-Boomer-/assets/110447589/9f3873bd-852b-460a-9c04-6cb92bc6f03a)

![Screenshot (42)](https://github.com/ankittbisht/SocialMediaApp-Boomer-/assets/110447589/b0518eac-a4a6-4d88-aa5f-fea992b0882c)


## What you need to run this code
-  Node  
-  NPM  
-  MongoDB   
    
## Run Locally

Clone the project

```bash
  git clone https://github.com/ankittbisht/SocialMediaApp-Boomer-
```

Go to the project directory

```bash
  cd SocialMediaApp-Boomer-
```

Install dependencies 
-  Go to client folder
```bash
  npm install
```
-  Go to server folder
```bash
  npm install
```
create .env file in server folder and write below content in it
```bash
MONGO_URL = 'change this to your mongodb url'
JWT_SECRET = 'yedilmaangemore'
PORT = 3001
```
change .env file in client folder and write below content in it
```bash
REACT_APP_SERVER_URL = 'http://localhost:3001'
```
Start the server  
- Go to client folder 

```bash
  npm start
```
- Go to server folder 

```bash
  node index.js
```

## Tech Stack

**Client:** React, Redux, JWT

**Server:** Node, Express

**Database:** MongoDb

