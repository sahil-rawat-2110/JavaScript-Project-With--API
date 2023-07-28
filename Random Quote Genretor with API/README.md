Project Folder Structure:

The project folder is named Random Quote Generator with API. Inside this folder, we have an HTML document – index.html. A Stylesheet – style.css.A script file – script.js and lastely a Readme file - README.md.



---------------------HTML----------------------

The HTML code consists of a div with a class wrapper. Within the wrapper, we have a div with a class name container. The container consists of a p element with an id quote. It also consists of an h3 element with id author.

Lastly, we add a button to this container with id btn.


---------------------CSS-------------------------

Now let us add some styles to this generator to make it look more fun. For this we use CSS.

We begin by removing unwanted paddings and margins from all the elements. We then set a bright red colour as the background colour of the document body.

In the next step, we add dimensions to the wrapper and centre it using CSS transforms. We also add dimensions to the container and set its background colour to #f43543. And to add more style to it, we add style box-shadow and border-radius.

We create a white coloured box behind the container to make it look even sleeker. To create this box we use the after pseudo-element.
We now style p and h3 tags as per our choice. I am using shades of white as text colour for the quote along with some other font properties.

In the final step, we style the button. We set the background colour to #ffffff and remove the unwanted order. We also set the border-radius to 5px. Lastly, we customize the font.



------------------JavaScript----------------------

We add functionality to this quote generator using javascript. We select the quote, author and btn element and assign them to different variables.
Similarly, we then create a variable called url that stores the URL to our API as a string.

Firstly, we create a function called getQuote(). Inside this function, we fetch the URL and get a JSON response. This response is basically a JSON object. Now we have to go through this data and select the content of our choice.

Here item.content gives us the quote while item.author gives us the author name. We then change the text content of quote and author to item.content and item.author respectively.

We call the getQuote() when the load event is triggered on the window element or the click event is triggered on btn element.