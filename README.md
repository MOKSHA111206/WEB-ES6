# ES6 Standards and Promise Concept

## Aim
To develop a JavaScript application using ES6 features and the Promise concept to simulate an asynchronous operation and display the result after successful completion.

## Files
- `index.html` - HTML structure and JavaScript Promise application.
- `style.css` - Styling for the application.
- `README.md` - Experiment details and instructions.

## Software Requirements
- Web browser (Chrome, Edge, or Firefox)
- Text editor (VS Code or Notepad)
- No additional library or installation required

## ES6 Concepts Used
- `let`: Declares a block-scoped variable.
- `const`: Declares a variable that cannot be reassigned.
- Arrow function (`=>`): Provides shorter function syntax.
- Template literals: Embed variables using `${}`.
- Promise: Represents the eventual success or failure of an asynchronous operation.
- `.then()`: Handles successful completion.
- `.catch()`: Handles errors or rejection.
- `.finally()`: Executes cleanup code regardless of success or failure.

## Procedure
1. Create a folder named `ES6PromiseLab`.
2. Save `index.html`, `style.css`, and `README.md` in the same folder.
3. Open `index.html` in a web browser.
4. Click **Start Operation**.
5. Observe the loading message and final result.

## Expected Output
- Initially: `Waiting to start...`
- After clicking: `Operation is in progress...`
- After approximately 2 seconds: `Operation completed successfully!`

## Testing Failure
Change `const success = true;` to `const success = false;` in `index.html` to test the rejection path.

## Result
Thus, a JavaScript application was implemented successfully using ES6 standards and the Promise concept to simulate asynchronous execution, handle success and failure, and display the result.
