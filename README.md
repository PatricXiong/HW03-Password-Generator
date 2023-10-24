# HW03-Password-Generator
Password Word Generator for Bootcamp

Summary
HTML and CSS and Javascript documents create a random password generator
This project emphasizes the use of using Javascript to make dynamic changes to an HMTL document

This project has the following features:
A generate button
After user data is collected, a random password will be generated using Javascript

I prompted to choose from the following password criteria: 8 and 128 characters
Password containing special characters, numbers, and uppercase
Either 4 variables individual ones, or 3 with toLowerCase to Uppercase conversion
The application should validate user input and ensure that at least one character type is selected.
If, else if statement
Once all prompts are answered, the user will be presented with a password matching the answered prompts. Displaying the generated password in an alert is acceptable, but attempt to write the password to the page instead.
Event listener will determine the password output with function to populate the value into the test area.
Copy execCommand in event listener
This project has script features of:
Variable declaration area
An event listener (onclick) called generatePassword
This will prompt the user for input between 8-128
This variable is changed to an interger using ParseInt()
This will validate that the input is a number within range, or is a number
This then uses the input to determine the types (or choices) or letters of characters used, using an if statement
This then assigns values to the variables using arrays for character, number or alphabet
Another variable is created to concatenate the above variables
A for loop will loop through the enter prompt until it reaches the number entered by user.
A password variable takes the value from the for loop, and converts it to a string.
The string value then populates into the text area for the user using a UserInput function.
An event listener (onlick) has also been created for the copy to clipboard feauture.
This project has media Queries for:
max-width: 980px
Adjusts body and container width
max-width: 786px
Adjusts body and container width
Adjusts buttons
max-width: 640px
Adjusts body and container width
Adjusts buttons to be centered and stacked


Creator: 
Patric Xiong
NorthWestern BootCamp