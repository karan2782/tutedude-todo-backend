## Todo backend 

### Run this repo on local steps:
- Firstly clone this repo on your local -> git clone http......
- After clone install express, mongoose, mongodb, dotenv, -> npm install run this command 
- Set enviroment variable with variables --> PORT=, MONGODB_URI=



### After Running this you can test api in postman:
#### Endpoints:
- Create a todo, Method will be POST --> /todos
- Get all todos , Method will be GET --> /todos
- Get a specific todo by its id, Method will be GET --> /todos/:id
- Update a todo by its id, Method will be PATCH --> /todos/:id
- Delete a todo by its id , Method will be DELETE --> /todos/:id


### Structure of the repo 
- server.js is the main file
- conntection.js file has access of the mongodb
- model folder has todoModels.js file has schema defined of the todo
- routes has todoRouter.js file has all routes of the todo
- controllers has todoControllers.js file has all logic of Create, Read, Update and Delete logic.
- .env file has enviroment variable
- sample.env file to see what kind of variable inside .env , I cannot push .env directly because it has sensitive information. 
