# Unhandled Exception Error in JavaScript within HTML
This repository demonstrates an uncommon error that can occur when using JavaScript within HTML. The error arises from attempting to modify the innerHTML of an element that does not exist on the page. 

## Description
The `bug.html` file contains a simple HTML structure with a div element that might not be found by the javascript code. The JavaScript code attempts to set the innerHTML of this element.  If the element with the id "myDiv" is not found, it will throw an error. This is a common error if the DOM is not fully loaded or an element has been removed before the script runs.

## Solution
The `bugSolution.html` file provides a solution to the problem by checking if the element exists before attempting to modify its innerHTML. Using this approach helps prevent unhandled exceptions.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the error in the browser's console.
4. Open `bugSolution.html` to see the corrected version.