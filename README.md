# different-weather-types

A JavaScript simple else...if statements for different types of weather

Code learning done from [here](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals) and check out the live page [here]( https://101010coder.github.io/different-weather-types).

# Details from the lesson:

> 1. Here we've got an HTML <select> element allowing us to make different weather choices, and a simple paragraph.
  > 2. In the JavaScript, we are storing a reference to both the <select> and <p> elements, and adding an event listener to the <select> element so that when its value is changed, the setWeather() function is run.
  > 3. When this function is run, we first set a variable called choice to the current value selected in the <select> element. We then use a conditional statement to show different text inside the paragraph depending on what the value of choice is. Notice how all the conditions are tested in else if() {...} blocks, except for the first one, which is tested in an if() {...} block.
  > 4. The very last choice, inside the else {...} block, is basically a "last resort" option — the code inside it will be run if none of the conditions are true. In this case, it serves to empty the text out of the paragraph if nothing is selected, for example, if a user decides to re-select the "--Make a choice--" placeholder option shown at the beginning.
