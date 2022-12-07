# NotesApp

## What are we going to learn Today? - MERN Stack
- Mongo
- Express JS
- React Js
- Node JS

### Building a notes app using MERN stack.

![image](https://user-images.githubusercontent.com/56730716/206178185-ba68fc72-62a1-491e-aab8-7ceb0d5721bb.png)


![image](https://user-images.githubusercontent.com/56730716/206151675-944718aa-5376-41a6-89e2-c2a7e888c79c.png)

### Prerequisites
Node JS Installed

```
cd NotesApp
```

#### Backend
First we create the server using:

https://expressjs.com/en/starter/hello-world.html

Some packages that we will be needing
- cors -> To make the API request from client
- body-parser -> To make REST APIs
- mongoose -> To connect to mongoDB database

Once the server is created,
```
cd server
npm install
npm install cors body-parser mongoose
```

Read the documentations and add all of these.

#### Database Setup
Use `mongoDB Atlas`, create a cluster.

#### Frontend
Go to the root folder
```
npx create-react-app client
```

In react, everything can be treated as a component. A component can be of two types.
Class Component and Functional Component

Some key terms to understand
- State - Dynamic values which defined the current situation and values
- Props - Properties that we pass to a component


React Hooks
- useState
- useEffect
