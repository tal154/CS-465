# CS-465

## Architecture

### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

In this project I utilized HTML & JavaScript using Express and Angular as my frontend architectures. On my customer facing side, I used HTML documents with JavaScript to display data served by Express. Multiple pages were loaded one at a time per user request via MVC architecture. Angular was used on the administration facing side. Using Angular, I created multiple components that were loaded programatically within the same HTML document. Single page applications, or SPAs, were used to allow admins seamless transitions to navigate the site. This is done by preloading all the documents so the code was already available. This is opposed to having to loading and caching a new page everytime. 

### Why did the backend use a NoSQL MongoDB database?

On the backend, I utilized noSQL MongoDB because it works well with Node.JS and its ease of modifying schema basedon scailing and functionality. An advantage of using MongoDB is it scales well horizontally and there are less transformations needed to be done for storing or retriving data for use. 

## Functionality

### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON was used for this project to store and display data. JSON, or JavaScript Object Notation, is frequently used when sending data to or from a server and formats data in a user-friendly objects. JavaScript is a common language used by developers to manipulate the way their webpages behave. One difference between JSON and JavaScript is JSON can be created and used by other programming languages as its data type is in key/value pairs separated by commas. JavaScript, on the other hand, can only be used in JavaScript. The reason behind JSON being able to tie together the frontend and backend development pieces is because this project uses MongoDB; MongoDB stores data in binary JSON, or BSON, format. Data can then be pulled from MongoDB and reformated to JSON to be used in a variet of ways. 

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

An instance that code was refactored to improve functionality and effiency is the trip card vs trip list components. Although using two componnets that render the same information is inefficient, having each trip being rendered separately but part of the whole works better in teh overall functionality of the site; having two objects provide parts for one function makes it easier to fix mistakes. For example, if the error occurs on every card, then the problem is in the card component. Reusing UI components is benificial because it decreases overall size of an application, making the development process quicker, and decreses the possiblity of errors and vulnerabilities being introduced into the system. 

## Testing

### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.

There are a few ways tof testing endpoints prior to adding security. The first is using the localhost web address for the API endpoitns to see if the page successfully loads the data or what type of error it throws. Using applications that test HTTP requests, like Postman, is ideal because it can also take secuiryt measures and inputs into place to test endpoints that might be protected from unauthenticated users.

### Explain your understanding of methods, endpoints, and security in a full stack application.

In a full stack application, methods like GET, POST, PUT, and DELETE are what drive the functionality of a webpage. These methods are http requests that can be used to retrieve or modify the database so the functionality can be implemented. These are driven on the backend by using the functions of the database (.create, .findOne, etc.) to modify the database. Endpoints are the resulsts of the methods seen by the admin or client side of the application. Endpoints should be tested so they funciton how they are intended to, display data properaly, and throw errors when they occur. Security is another layer of code that is added to preven unauthorized or unauthenticated users from access or modifying the database. In this project, the add and edit buttons on the admin side of the application are not visable until a authorized user is logged in. This protects the API endpoints so only authorized users can modify the database.

## Reflection

### How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

One of my main goals of pursuring this Computer Science degree is because my friend has offered me a job for backed development for his company once I finish. As such, this class has helped me immensely because this is the kind of work I will be working on should I get the job. The skills I have learned in this course that will help me become more marketable in my career field is being able to work on both frontend and backend development using MEAN full stack tools. My understanding of the tools of MEAN has improved greately thanks to this course. While I still have much to improve on, the skills I better understand are beter understanding of Git and using different modules or components linked together to build a finished product. 
