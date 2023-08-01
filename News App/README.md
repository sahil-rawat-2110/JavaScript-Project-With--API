Project Folder Structure:

Let’s build the project folder structure before we begin writing the code. We create a project folder called ‘News App’. Inside this folder, we have index.html, style.css, script.js, and API-key.js.




HTML:

We begin with the HTML Code. First, create a file called – ‘index.html’. 



CSS:

Next, we style our list using CSS.




Javascript:

Finally, we add functionality using Javascript.

Before moving to actual implementation we store the API key in the file ‘api-key.js’. Then let’s move on to the implementation steps:

Create initial HTML references and store the API URL in a variable
Create buttons for options stored in the options array. When the user clicks on any option we append the category to our URL and make another call to get new results.
Then create the function ‘getNews’ to make a request to the API and get a response with all news articles or an error. In case of an error we display a message and stop code execution else we call the function ‘generateUI’.
In the ‘generateUI’ function we create a card for each article and append it to our container to display all the news articles.
 