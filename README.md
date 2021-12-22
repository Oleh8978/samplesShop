  Intro<img width="1437" alt="Screenshot 2021-12-23 at 01 33 43" src="https://user-images.githubusercontent.com/53382946/147166540-cdc3b25f-5b62-42d0-96ab-b4ea3c11beb9.png">
<img width="1422" alt="Screenshot 2021-12-23 at 01 34 25" src="https://user-images.githubusercontent.com/53382946/147166574-af3e2379-aac2-4790-8a71-f0be3c5a66ee.png">

  
I worked on this project with huge presure and with small time frames. Code isn't perfect but you can see samples of my work on open sourse projects like that.

So, consider this as a learning example or just a showcase rather than a production-quality code.

  Description
Shopping cart app build with MERN stack and using RESTful API design. Responsive front-end design done with Material-UI, uses Redux for state management, Node & Express for API, MongoDB as database. App runs in Docker containers but you can also run each sub-app separately, without Docker.

You can get and view the list of all products from the API, register, add products to cart, remove specific product or empty entire cart, make order...

Technologies & Tools:
  Front-end:
  React
  Redux
  Redux-Saga
  Material-UI
  Webpack
  TypeScript
  Backend:
  Node/Express
  MongoDB/Mongoose
  Installation and Usage
  Requirements:
  Docker
In case you want to run it without Docker (requires additional setup):

  Node.js installed
  MongoDB connection
  
  Steps:
Clone repo on your local machine,
Run docker-compose

$ docker-compose up -d

This will pull images and build 3 containers for each part of the application: frontent, backend & db.

  If everything went without problems, go to localhost:3000, you should see the running app.
frontend container (React app) runs on port 3000
backend container (Node api) runs on port 5000
db container (MongoDB server) runs on port 27017
Use docker exec -it <container name> bash to troubleshoot if there are any problems.
