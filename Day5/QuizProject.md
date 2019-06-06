# Quiz Project
Create a simple quiz about yourself using JavaScript! Start from a new CodePen: https://codepen.io/pen/

## Part 1 - HTML setup
1. In the HTML section, create a large header saying "My Quiz"
1. Under the large header, create a button with the text "Begin"
    - In the button, set the `onclick` attribute to call the `beginQuiz()` function

## Part 2 - CSS setup
1. In the CSS section, create a new **ruleset** for the `body`
    - Set the `background-color` to a color of your choosing (e.g., "black")
    - Set the `color` to a color of your choosing (e.g., "pink")
    - Set the `font-family` to a font of your choosing (e.g., "consolas")
    - Set the `text-align` to an alignment of your choosing (e.g., "center")
1. Create another new **ruleset** for only the `button`
    - Set the `font-size` to a size of your choosing (e.g., `20px`)
    - Set the `background-color` to a color of your choosing (e.g., "pink")

## Part 3 - JavaScript setup
1. In the JavaScript section, define a new function named `beginQuiz`
    - `function`
    - name (`beginQuiz`)
    - parentheses (`()`)
    - curly brackets (`{}`)
1. At the top of the body of the `beginQuiz` function, define a new variable named `points`
    - Set its value to `0`
1. At the bottom of the body of the `beginQuiz` function, display a message to the user telling them their score
    - Their score should be the number of points they earned divided by the total number of questions
    - For an added challenge, display their score as a percentage
    - For another added challenge, if the user answered all the questions correctly, change the background color to green!

## Part 4 - Questions
Add at least 5 questions to the quiz. Questions should go between the `points` variable initializer and the final score message. To ask and score a question:

1. Use a `prompt` to ask the question
    - Store the user's answer in a variable
1. Use an `if` to check for the correctness of the answer
    - `if`
    - parentheses
    - condition (e.g., `answer === "Correct"`)
    - curly brackets
1. If the answer is correct, increment the value of `points` by 1
    - Do this within the brackets after the condition
    - `points = points + 1`

Repeat the steps above for multiple different questions. Each time a question is added, be sure to update the final score calculation!

## Bonus - Multiple Choice Questions
Ask some multiple choice questions in addition to regular questions. To make this look nice, use the newline character `\n` to create a new line in the text box. Alternatively, instead of using double quotes, use backticks (`\) and put the new lines right in the string!

#### Example
```js
var answer = prompt(`Where are you from?
A) Utah
B) South Carolina
C) Ohio
D) California`);
```