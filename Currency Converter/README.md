Project Folder Structure:

Let’s build the project folder structure before we begin writing the code. We create a project folder called ‘Currency Converter’. Inside this folder, we have index.html, style.css, script.js, currency-codes.js, API-key.js, and SVG icon files.



-----------------------HTML--------------------

We begin with the HTML Code. First, create a file called – ‘index.html’. 



-----------------------CSS--------------------

Next, we style our list using CSS.



--------------------Javascript--------------------

Finally, we add functionality using Javascript.

Before moving to actual implementation we store the API key in the file ‘api-key.js’ and store all the currency codes in the ‘currency-codes.js’ file.

Then let’s move on to the implementation steps:

Create initial HTML references and store the API URL in a variable
Fill Currency codes in dropdown options
When the user clicks on the convert button or when the page loads we call the ‘convertCurrency’ function
The ‘convertCurrency’ function stores the values of both the dropdowns that the user has chosen or based on default values
Now if the user hasn’t submitted a blank amount we make a GET request to the API URL using the ‘fetch’ method.
The API returns current rates for each currency
Now we convert the entered amount to another currency using the fetched rate and display it upto two decimals