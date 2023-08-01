
# Boomer - SocialMedia App
This MERN app is a responsive web application with authentication and dark mode support, leveraging Material-UI (MUI) for a modern UI design.

Key Features:
- Users can register, login, and logout securely using JSON Web Tokens (JWT).
- The app also comes with a login page that ensures authenticated access to protected routes.
- Users can post content and interact with it by liking and disliking posts, with the number of likes displayed.
- The mobile-first design ensures a seamless user experience on various devices.
- The app is powered by MongoDB for data storage and Express.js for the backend API, enabling efficient data management and retrieval.

## Live Demo
https://socialmedia-boomer.netlify.app/



## Screenshots

![Screenshot (41)](https://github.com/ankittbisht/Keeper-Application/assets/110447589/6244d80f-4506-4ca3-9de5-8c7e361acc39)
![Screenshot (42)](https://github.com/ankittbisht/Keeper-Application/assets/110447589/d6307f25-ad78-4a84-afd1-235a2dd660a5)
![Screenshot (43)](https://github.com/ankittbisht/Keeper-Application/assets/110447589/a5049444-9efb-43e5-8dab-90edec959e60)
![Screenshot (47)](https://github.com/ankittbisht/Keeper-Application/assets/110447589/da3730d7-fc07-4367-bfd3-20ef874bd64a)



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

## Contact

If you have any questions, suggestions, or just want to say hi, feel free to reach out to me.

- **Email:** [ab67743@gmail.com](mailto:ab67743@gmail.com)
- **GitHub:** [ankittbisht](https://github.com/ankittbisht)
- **LinkedIn:** [ankittbisht](https://www.linkedin.com/in/ankittbisht/)

I'm always open to collaborating on exciting projects or discussing new ideas. Don't hesitate to connect!



