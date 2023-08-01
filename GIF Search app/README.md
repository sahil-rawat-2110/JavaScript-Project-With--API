Project Folder Structure:

Let’s build the project folder structure before we begin writing the code. We create a project folder called ‘Gif search app’. Inside this folder, we have index.html, style.css, script.js, and API-key.js.



------------------HTML----------------

We begin with the HTML Code. First, create a file called – ‘index.html’.


------------------CSS----------------

Next, we style our list using CSS.




----------------Javascript----------------

Finally, we add functionality using Javascript.

Before moving to actual implementation we store the API key in the file ‘api-key.js’.

Then let’s move on to the implementation steps:

Create initial HTML references and store the API URL in a variable
Call the “generateGif()” function when the user clicks on the submit button or when the window loads
The “generateGif()” function displays a loader until all the GIFs have loaded and makes a call to the Giphy API based on the search value or default value.
After that, we create a card for each gif we get in response. The card displays the gif and a copy link button that allows the user to copy a link to the GIF to their clipboard.
If the user’s browser does not support the clipboard API, we create a temporary input field to copy the GIF link to the clipboard.