# WeChat App
Realtime chat app with websockets using Node.js, Express and Socket.io with Vanilla JS on the frontend. 

A real time chat application that sends and shows messages to a recipient instantly without any page refresh. 
We will use the JavaScript framework Express.js and the libraries Mongoose and Socket.io to achieve this.
This app will allow multiple users to chat together.

//STEP 1 
We can start by creating a new project directory and moving into it. 
Then we can initiate our project by the following command:
        npm init
This will prompt us to enter details about our project.
After which a package.json file will be created and our App directory is now set.

//STEP 2
Install the server using Express Framework.
Express  provides a robust set of features for web and mobile applications. 
Express provides a thin layer of fundamental web application features, without obscuring Node.js features.
        npm install express

//STEP 3
Create a server.js file 
In this file we need to require Express and create a reference to a variable from an instance of Express. 
Static contents like HTML, CSS or JavaScript can be served using express.js:
And start listening to a port

//STEP4
We would install a package called nodemon.
This allows changes made in the code to be automatically detected. 
        npm install nodemon --save -dev
        npm install -g nodemon //This allows global accessibility

//STEP 5
We need to create an HTML file index.html that displays our UI. 
I have added bootstrap and JQuery cdn.

//STEP 6
We would now create our database and connect it to the app using Mongoose
For this app we will be using a No-SQL database (Mongodb).
Our database will contain a single collection called messages with fields name and message.

//STEP 7
We would install Body-Parser package
This package extracts the body portion of an incoming request stream and exposes it on req.body
        npm install body-parser

//STEP 8
We define routing using methods of the Express app object that correspond to HTTP methods: 
app.get() to handle GET requests and app.post() to handle POST requests.
Routing refers to how an application’s endpoints (URIs) respond to client requests.

//STEP9
We will intall Socket.IO and HTTP package for Socket.io to work.
Socket.IO is a JavaScript library for realtime web applications. 
It enables realtime, bi-directional communication between web clients and server. 
It has two parts: a client-side library that runs in the browser, and a server-side library for Node.js. 
Socket.io enables real-time bidirectional event-based communication.
        npm install socket.io
        npm install http


//STEP10