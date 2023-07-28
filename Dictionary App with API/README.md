--------------Project Structure--------------
The project structure is called Dictionary. Within this folder, we have three files :
a an HTML document, a stylesheet and a script file. Name them index.html, style.css and script.js respectively.
 
----------------HTML--------------

Let us start by coding the HTML part first.
The HTML document consists of a container div to wrap and centre all the other elements. Inside the container, we have a div called a search box. The search box consists of an input type text and a button. Apart from this, the HTML code consists of an audio tag and a result div.

----------------CSS--------------

We make the dictionary presentable by adding some styles to it using CSS. I have used the flex layout to position and space elements. The rest of the styling is pretty self-explanatory.


--------------Javascript--------------

To add functionality to the dictionary we use javascript.

In javascript, we use a URL that we have obtained from the dictionary API website and assign it to a variable called url. We target other elements and assign them to variables too.
We add an on-click event listener to the button. The user input word is stored in a variable called inpWord. We fetch the URL and get a JSON response. This response is in the JSON object. Now, we need to create HTML elements via javascript. Next, we search the JSON object to get the needed data. We display each of these data in the appropriate HTML element.
To play the pronunciation audio we create a function called playSound(). Inside this function, we call the play() on the audio file.