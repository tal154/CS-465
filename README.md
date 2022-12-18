# CS-465

## Architecture

### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

In this project I utilized HTML & JavaScript using Express and Angular as my frontend architectures. On my customer facing side, I used HTML documents with JavaScript to display data served by Express. Multiple pages were loaded one at a time per user request via MVC architecture. Angular was used on the administration facing side. Using Angular, I created multiple components that were loaded programatically within the same HTML document. Single page applications, or SPAs, were used to allow admins seamless transitions to navigate the site. This is done by preloading all the documents so the code was already available. This is opposed to having to loading and caching a new page everytime. 

### Why did the backend use a NoSQL MongoDB database?

On the backend, I utilized noSQL MongoDB because it works well with Node.JS and its ease of modifying schema basedon scailing and functionality. An advantage of using MongoDB is it scales well horizontally and there are less transformations needed to be done for storing or retriving data for use. 

## Functionality

### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON was used for this project to store and display data. JSON, or JavaScript Object Notation, is frequently used when sending data to or from a server and formats data in a user-friendly objects. JavaScript is a common language used by developers to manipulate the way their webpages behave. One difference between JSON and JavaScript is JSON can be created and used by other programming languages as its data type is in key/value pairs separated by commas. JavaScript, on the other hand, can only be used in JavaScript. The reason behind JSON being able to tie together the frontend and backend development pieces is because this project uses MongoDB; MongoDB stores data in binary JSON, or BSON, format. Data can then be pulled from MongoDB and reformated to JSON. 
