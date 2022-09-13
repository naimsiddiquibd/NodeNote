----------------------------------
Setup A Node Project
----------------------------------
1. create a folder (manually or mkdir)
2. open command line to that folder
3. npm init -y
4. npm install express (https://expressjs.com/en/starter/installing.html)
----------------------------------
For Node Express Server
----------------------------------
5. Use the starter template (https://expressjs.com/en/starter/hello-world.html)
6. Change port 3000 to 5000
7. To run the server: node index.js
8. Check browser for the port
9. Change the port: process.env.PORT || 5000
10. To setup auto update functionality: npm install -g nodemon (https://www.npmjs.com/package/nodemon)
11. Add the "scripts" inside the "package.json":<br>
    "start": "node index.js",<br>
    "start-dev": "nodemon index.js",<br>
12. Now to run the server: nodemon index.js<br>
-----------------------------------
Get API
-----------------------------------
13. Create API, Dynamic API, Params (https://github.com/naimsiddiquibd/DinamicAPI-Parameter-PARAMS/blob/main/index.js)
14. npm install cors (to use server side API to client side)<br>
    require cors: const cors = require('cors');<br>
    Add a middleware: app.use(cors());
-----------------------------------
Post API
-----------------------------------
15. Create: client side, form, submit button, get value from inputs, onSubmit function, Send data to the server (https://github.com/naimsiddiquibd/react-project-1/blob/main/src/App.js)
16. From the client side: Upload JSON data (https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
17. Add a middleware: app.use(express.json());
18. From the server side: Get te value of the "req.body";, change the new post's id number to "friends.length + 1";, push it to the main array, "res.send(friend)"; (https://github.com/naimsiddiquibd/DinamicAPI-Parameter-PARAMS/blob/main/index.js Line: 39-45)
-----------------------------------
Query Parameter
-----------------------------------
19. To search on browser's link box: http://localhost:5000/friends?name=naim
20. In the server side: (https://github.com/naimsiddiquibd/DinamicAPI-Parameter-PARAMS/blob/main/index.js Line: 23-30)
-----------------------------------
Git Ignore
-----------------------------------
21. Create a file by clicking package.json: .gitignore
22. Write what you want to hide: node_modules