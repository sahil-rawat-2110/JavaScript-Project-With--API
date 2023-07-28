Project Folder Structure:

Let us take a quick look at the project structure. We have a project folder called – Pokemon Card Generator with API. Inside this folder, we have three files. The first one is the HTML document called index.html. Next one is the stylesheet named style.css, and the last one is the script file called script.js and last one is readme file which is README.md.



--------------------HTML------------------

The HTML consists of a container div that wraps the card div and the button element. We don’t have many other elements in HTML code as we will be generating them using Javascript.



--------------------CSS--------------------

Coming to the CSS Code, we do a CSS reset by removing the unwanted paddings and margins. We also centre the container using the transforms. We set the dimensions for the container and the card div.

For the pokemon image we set the width to 180px and max-height to 200px.
We style the span elements and place them inside the types div using the flex layout. We set the justify-content to space-around.

Similarly, we style the stats div and the button.



--------------------JavaScript--------------------

Now coming to javascript, we create an array for colours corresponding to each pokemon type. Next, we store the pokeAPI link in a constant called URL. We also get the card and btn elements and assign them to variables.

In the next step, we create a function called getPokeData. Within this function, we generate a random number between 1 and 150. This number will be our id.

We create the finalUrl by combining the URL and the id string. Now we fetch the data for the pokemon corresponding to the id generated. We use this data to create the card.

For the next step, we create a function called generateCard(). Now using the data fetched from the API we get necessary data and assign them to variables.

We now use the pokemon type to get a corresponding color value from the typeColor array. Now we assign this value to a variable called themeColor.

Next, we generate HTML for the card using variables we have created. At this point, we call the function appendTypes with the parameter data.types.
The appendTypes function iterates over the types array and wrap each type inside a span element. This span element is then appended to the types div.

We also call the styleCard function which applies the themeColor to the card background as radial-gradient and the span element inside the types div. And that’s it. Our random pokemon Card generator is now ready.