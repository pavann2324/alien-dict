## Alien Dictionary
This project provides a web-based tool to determine the order of characters in an alien language based on a sorted list of words. The user inputs words that follow the lexicographical order of the alien language, and the application computes the character order.

## Features
Interactive Interface: Input a list of sorted words to find the alien language's character order.

## Graph Algorithm: Uses topological sorting to determine character precedence.

**Error Handling:** Notifies the user of invalid inputs or inconsistent word orders.

## Technologies Used
HTML: Structuring the interface.

CSS: Styling the interface with a modern gradient and responsive design.

JavaScript: Implementing the core logic for topological sorting and character order determination.

## How It Works
Enter words in the provided text area, one per line, ensuring they are in lexicographical order according to the alien language.

Click the "Find Character Order" button.

The application processes the input:

Builds a directed graph of characters.

Performs a topological sort to deduce the character order.

Checks for cycles or invalid input sequences.

Displays the result or an appropriate error message.

## Input Format
Words should be entered one per line.

Words must follow the lexicographical order of the alien language.

##Example Input:

nginx
Copy
Edit
wrt
wrf
er
ett
rftt
## Output
Displays the character order as a string.

If the input is invalid, shows an error message.

## Example Output:

sql
Copy
Edit
Character order: wertf
## How to Use
Open the index.html file in any modern web browser.

Enter the input words in the text box.

Click the button to compute the result.

View the character order or error message in the output area.

Files
index.html: The main application file containing HTML, CSS, and JavaScript.

Deployment
You can host the file on any static web server or simply open it locally in a browser.


Happy decoding alien languages! 🚀
