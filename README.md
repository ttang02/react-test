# react-exam 

This app is the OFFICIAL **jedi management tool**. For now, it only
displays the most famous of them.
 
Our CTO has looked at the source code and has seen that it doesn't follow
good practices.
He also wants to add a new feature to the app: The ability to register 
a new jedi.

## Tasks
### Clean up
Clean up the project and make it follows react/redux app good
practices. This will help you to add to it more features.

### Add a new jedi to the DB
Create all the necessary things to register a new jedi.

Hint: All files that you should modify are in `./src`

## Getting started
Launch the front-end server with:
```
npm start
```

Launch the API server (in a second terminal) with:
```
npm run api
```

Be sure that the project is compiling before pushing with the command:
```
npm run compile
```

## How to?
Fork this project and create a pull request on this repository from your fork.

---

Step 1 : 

Clean up src and separate into different folders.

- Components
- Actions 
- Reducers

Step 2 : 

Split the component App into differents components

- One for the list of Jedis
- One for the detail of one Jedi.
- One to register a new jedi.

Step 3 : 

Review Redux architecture and add function for adding a new jedi.

- Add addnewJedi into action.js
- Add a form
