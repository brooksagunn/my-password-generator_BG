## my-password-generator-bg

# HTML
* Utilized HTML from Trilogy 03-JS Homework File
* Added descriptive comments to make for easier reading
* Added script tag for Rando js - a randomizer based on a refined Fisher-Yates shuffle 
# CSS
* Utilized CSS from Trilogy 03-JS Homework File
# JS
* _writePassword()_
* Saves the string produced by generatePassword to a variable - password; passwordText selects the "password" id element and its value is set to the string in password, displaying the string as text on the page
* _generateBtn.addEventListener()_
* Runs writePassword function when the password generation function is clicked
* _generatePassword_
* Empty vars for setup
* Arrays hold characters based on type
* Prompts user to enter a password length between 8 adn 128 characters
* Saves confirmed true or false value for each type choice based on user input
* Confirmation values stored in array
* If chosen password length is out of bounds, an alert tells the user that they should enter a character length within the bounds, and then it recursively calls generatePassword
* While the new iterator i is less than the length of the allChars array, then function checks if the element in allChars evaluates to true; if the element evaluates to true, its corresponding array is chosen from allArrays and a character is chosen from the array to be added to the unradomized password stored in passKey
* As long as the num iterator is less than length of the allChars array, each confirmation that evaluates to true in allChars is concatenated to the pool of chosen characters from which the password will be forged
* While the iterator i is less than the chosen length of the password, if the pool of chosen characters has more than 0 elements concatenated to it, an unrandomized password will be continued if added to earlier and generated fully; the password takes takes random characters from the pool and i is iterated up by one; otherwise, the system will ask for the user to choose at least one character type for their password and recursively call the function
* Randomizes unrandomized passKey using refined Fischer-yates shuffle from random.js
* Returns shuffled key string
# LINKS

# E-SIGNATURE
Brooks Gunn :)

![screenshot](Assets\my_password_generator.png)