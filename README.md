The location of your “server.js” is VERY important. 
For now, we will have the server.js INSIDE the react project folder. 


Create the react app
Make a small change in app.js
Make a server.js INSIDE the react folder (same level as src)
Add the “express.static” line you can find in any of our projects
Should use path.join with __dirname and “build”
Install express and path pkg
Upload to github
Make new web service on Render
Build command should be “npm install && npm run build”
Start command should be “node server.js” to start your server
