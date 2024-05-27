
# TODO APP

This application allows users to manage todos within projects. It supports creating new projects, managing todos (add, edit, update, and mark as complete), and exporting project summaries as secret gists on GitHub.


## Features
- JWT token-based authentication for user login
- Home page with project listing ,view projects and creation of new project
- Detailed project view with editable title and todo actions
- Manage todos within a project (Add, Edit, Update, and Mark as complete)
- Export project summary as a secret gist on GitHub



## Technologies Used

- Frontend: React (Create React App), Axios
- Backend: Node.js, Express, MongoDB, Mongoose
- Authentication: JWT (JSON Web Tokens)
- GitHub API for Gist creation

##  Prerequisites

- Node.js (v14 or higher recommended)
- npm or Yarn
- MongoDB
- GitHub account (for creating gists)
##   Getting Started

 ## Backend Setup

  **Clone the repository:**

   ```sh
   git clonehttps://github.com/denmd/todo_backend.git
   cd todo_backend  

```
**Install dependencies**
 ```sh
 npm install

```
**Run the backend server**

```sh
npm start
```

**Set up environment variables**
```sh
MONGO_URI=your-mongodb-uri
JWT_SECRET_KEY=your-jwt-secret-key
GITHUB_TOKEN=your-github-token
PORT=your-backend-running-port
```

## Frontend Setup

   ```sh
   git clone https://github.com/denmd/todo_frontend.git
   cd todo_frontend  
```

**Install dependencies**
 ```sh
 npm install

```

Run the frontend server for development

``` sh
npm start
```
Build the frontend for production
```sh
npm run build
```
base URL of the API server
```sh
http://localhost:PORT
```




## Testing
## Backend Tests
Implement tests using your preferred testing framework (e.g., Jest, Mocha).Then run
``` ssh
npm test
```
### Frontend Tests

Implement tests using your preferred testing framework (e.g., Jest, React Testing Library).Then run,

``` ssh
npm test
```


## Hosted URL

```sh
https://todoapp-6qiy.vercel.app/
```
