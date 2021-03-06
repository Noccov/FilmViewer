# FilmViewer
This is the application built for the CGI internship in spring 2020


Welcome to the FilmViewer app.

This application allows users to navigate a predetermined (hardcoded) list of films. 

On the UI side there are two components: the search component and a component for displaying movies. 
The search component has two options for filtering films: the searchbar, which displays all movies that include the searchterm and the
checkboxes, which allow the user to filter the list by genre. 

The backend runs on a ASP.NET MVC application. It has two API-s: sending the full list of movies as a JSON object and sending a single movie object by ID. All
this logic is included in the MovieController class.  
The backend has a Repository class, which holds the full list of movies as Movie objects. The Movie objects are stored in a MoviesList object. 
For retrieving the desired objects there is a MovieService class, which is tightly coupled to the Repository. 
The backend application runs in: https://localhost:44384/
The frontend application runs in localhost:4200.

To run the angular application you need to install node (node.js), angular CLI (npm install -g @angular/cli) and the 
angular development kit (npm install --save-dev @angular-devkit/build-angular) in order. 


------------------------------------------------------------------------------------------------------------------------------------------------------------------

Comments on the assignment

The hardest part for me was the frontend of this application. As I had almost no previous experience with any frontend building or frameworks, I spent most of the time 
on learning, testing and writing the frontend side of the code. Most of the frontend code and learning was from www.codewithmosh.com. The backend implementation of
this assignment was much easier to write, even though most of my experience is in Java. I think the similarities between Java and C# helped a lot.

In this implementation I tried to use the simplest and most modular approaches I could. As I have almost no experience in HTML and JS, the solutions are perhaps
redundant or feel patchy, but I have tried to use the object oriented approach and reusability principles I have learned in my previous experience to make this
application as simple and scalable as possible. 

I would very much appreciate a shot at the apprenticeship, any feedback is more than appreciated. 
