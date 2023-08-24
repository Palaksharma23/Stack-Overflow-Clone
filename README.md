

<h1 align="center"> Stack Overflow Clone 🚀</h1> 
<p align="center">
  <a href="https://stack-overflow-clone-y1fv.onrender.com/">
    <img alt="Stack Overflow Clone image" title="Stack Overflow Clone" src="https://i.ibb.co/TKHkYnP/Whats-App-Image-2023-08-24-at-9-23-39-PM.jpg" width="450">
    
  </a>
</p>

<p align="center">
Welcome to **Stack-Overflow-Clone**, a platform dedicated to fostering a vibrant community of developers helping developers by providing a space to ask questions, share knowledge, and find solutions together. 🌟❤
</p>

<p align="center">
  <a href="https://stack-overflow-clone-y1fv.onrender.com/">Stack Overflow Clone
  </a>
</p>


## Table of Contents

- [Important Links](#important-links-related-to-the-project)
- [Technology Used](#technology-used)
- [Features](#features)
- [Top Level Directory Structure](#top-level-directory-structure)
- [Screenshots of the project](#screenshots-of-the-project)
- [Installation](#installation)
- [Contributions](#contributions)
- [Usage](#usage)
- [Feedback](#feedback)


### Important links related to the project

* <b>Deployed website 👉: </b> [Stack-Overflow-Clone](https://stack-overflow-clone-y1fv.onrender.com/)

* <b>The backend is hosted here 👉: </b> [Stack-Overflow-Clone-Backend](https://stack-overflow-clone-server-ql8j.onrender.com/)


## Technology Used

| Technology | Features |
|------------|----------|
|   React.js      |  Frontend of the application |    
| Redux | State Management|    
| Node.js, Express.js    |  Backend of the application  |   
|    MongoDB Atlas, Mongoose    | Database for the application|
| Bcrypt     |    Password Management      |   
| JSON Web Token     |    Authorization and Authentication |
| Render     |     Deployment     |  
| Postman | API Testing, Debugging and Documentation |
 
## Features

Features of our Stack Overflow Clone are as follows:

- **Ask & Answer:** Post your coding questions and provide answers to help fellow developers.
- **Voting:** Upvote helpful questions and answers to recognize and encourage valuable contributions.
- **Tags & Categories:** Organize content by adding relevant tags and categories to questions.
- **Search:** Easily find answers using our powerful search functionality.
- **User Profiles:** Build your developer identity, showcase your skills, and keep track of your contributions.
- **Responsive Design:** Enjoy a seamless experience across devices, from desktop to mobile.

## Top-level directory structure

	├── client                   # Frontend React.js directory
	│   ├── public              # Public assets for the React app (images, etc.)
	│   ├── src                 # React application source code
	│   │   ├── components      # Reusable UI components
	│   │   ├── pages           # Individual page components
	│   │   ├── App.js          # Root component
	│   │   ├── index.js        # Entry point for React app
	│   │   └── ...             # Other React-related files and folders
	├── server                  # Backend Node.js/Express directory
	│   ├── controllers         # Controllers for handling requests
	│   ├── models              # Database models and schemas
	│   ├── routes              # API route handlers
	│   ├── utils               # Utility files
	│   ├── views               # Templates for rendering server-side views
	│   ├── app.js              # Express app setup
	│   ├── package-lock.json   # Node.js package lock
	│   └── package.json        # Node.js package information
	├── .gitignore             
	└── README.md


<div align="center">
<img src="https://i.ibb.co/BK8KLHM/MVC-Architecture.jpg" alt="mvc architecture" height="400"/>
</div>
<br/>

## Screenshots of the project
<table>
  <tr>
    <td>Home Page</td>
    <td>Tags Page</td>
  </tr>
  <tr>
    <td>
   <img src="https://i.ibb.co/gM7xXWr/screely-1692895310281.png" border="0">
    </td>
        <td>
<img src="https://i.ibb.co/t2mPvSw/screely-1692895676919.png" alt="screely-1677925947288" border="0"></td>

  </tr>
</table>
<table>
  <tr>
    <td>SignUp Page</td>
    <td>Login Page</td>
  </tr>
  <tr>
    <td>
<img src="https://i.ibb.co/vd9TjxS/screely-1692895003181.png" alt="screely-1677924790571" border="0"></td>
<td><img src="https://i.ibb.co/nc7vgn1/screely-1692894712324.png" alt="screely-1677925542185" border="0">
</td>
  </tr>
</table>
<table>
  <tr>
    <td>Question Detail Screen</td>
    <td>Posting an Answer Screen</td>
  </tr>
  <tr>
    <td>
<img src="https://i.ibb.co/M1n4dHf/screely-1692897031364.png" alt="screely-1677925947288" border="0"></td>
<td>
   <img src="https://i.ibb.co/TmSPn3k/screely-1692897192656.png" border="0">
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>All Users Screen</td>
    <td>Ask a Question Screen</td>
  </tr>
  <tr>
<td>
   <img src="https://i.ibb.co/Bym2PSg/screely-1692896520603.png" border="0">
    </td>
<td>
   <img src="https://i.ibb.co/YB4VDgq/screely-1692896859187.png" border="0">
    </td>

  </tr>
</table>
<table>
  <tr>
    <td>User Profile Screen</td>
    <td>Other User's Profile Page</td>
  </tr>
  <tr>
     <td>
<img src="https://i.ibb.co/3kPJWtS/screely-1692895544650.png" border="0"></td>
    <td>
<img src="https://i.ibb.co/LRv0rQh/screely-1692896637899.png" alt="screely-1677925947288" border="0"></td>
  </tr>
</table>



##  Installation
<br>

To setup the project on your local environment, follow the given steps:

1. Fork the [Palaksharma23/Stack-Overflow-Clone](https://github.com/Palaksharma23/Stack-Overflow-Clone) repository.
2. Clone the repository:
```
https://github.com/<USERNAME>/Stack-Overflow-Clone.git
```

  Replace the `<USERNAME>` with your GitHub username. 

  ### Frontend

Move to the client directory

```bash
  cd client
```

Install the necessary dependencies

```bash
  npm install
```

To start the server in development mode

```
  npm start
```

Go to `localhost:3000` to view the website.
<br>

### Backend

Move to the server directory

```bash
  cd server
```

Install the necessary dependencies

```bash
  npm install
```

Add a config.env file in the root directory and enter your MongoDb Atlas and JWT Secret key 
The format of .env file should be similar to the following
```
CONNECTION_URL = "Mongo db url"
JWT_SECRET = "This could be anything like test"
```
To start the server in development mode

```
  npm start
```

Server will start at `PORT 5000`
<br>

## Contributions

Your worthy contributions are most welcome to our Stack Overflow Clone website. If you have an idea for a new feature or a bug fix, please submit an issue or pull request.


## Feedback

Feel free to send any feedback on [Twitter](https://twitter.com/palaksharma2312) or [file an issue](https://github.com/Palaksharma23/Stack-Overflow-Clone/issues/new). 

