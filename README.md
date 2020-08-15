This project was created for the front end developer certification for FreeCodeCamp.com

You can read more about it [here](https://www.freecodecamp.org/learn/front-end-libraries/front-end-libraries-projects/build-a-javascript-calculator)

The development build passes 16/16 tests and took ~6 hours to build (first 3 were spent trying to recreate calculator functionality before discovering eval() method on the global object 😒)

In general it uses a switch statement to evaluate which button was pressed and then calls a custom function with if statements and regular expressions to check the the input for how to update the display. Then when enter is clicked it does a final check that the input is valid and then runs the eval function. 

You can view the demo here: https://howagain.github.io/fcc-javascript-calculator 