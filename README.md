# code-challenge-1

  Then load the module in our .js file using the below code

  ```js
  const prompt = require('prompt-sync')();
  ```
This line below will prompt user to enter a mark and store our input in studentMarks variable 
   ```javascript
       let studentMarks = prompt("Enter student's marks ? ");
       //This line below will display the entered marks back to the user.
        console.log(`Student's marks is :  ${studentMarks}`);
   ```
   This will store our users input in studentMarks variable 

  ### step 2

declare a function called grading where we use else-if to do our grading and console.log the outputs according to our criteria.
@@ -58,12 +62,21 @@ we call the grading function at the end
   ```
  ### step 3
  To run the .js file we use the following command in our terminal
        `node nameOfYourJsFile.js`

`node nameOfYourJsFile.js`

   enter any kind of input to see if the code runs successfully     
  ![Alt text](./example.png "sample outputs")
  ![Alt text](./image/example.png "sample outputs")
