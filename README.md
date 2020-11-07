# Web API: Code Quiz


## This Repository

This repository ("homework-week04") is where I have stored my changes to the assignment. This source code is available to everyone under the standard MIT license.

## Usage 

This project was designed as a homework assignment for OSU's coding bootcamp.

As I proceed in my journey to becoming a full-stack web developer, it’s likely that I'll be asked to complete a coding assessment, perhaps as part of an interview process. A typical coding assessment is a combination of multiple-choice questions and interactive coding challenges.

This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link. Or, download the sources files to use this as a template.

Here is the link to my application: [Web API: Code Quiz](https://nasgenius.github.io/homework-week04/)

## Getting Started

This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link. Or, download the sources files to use this as a template.

[GitHub Repository](https://github.com/NasGenius/homework-week04)
[Web API: Web Quiz]()

## Prerequisites

To view this code locally, you will need to download the zip file in this repo or utilize GitHub's guidelines to clone the repo. You will also need a teext editor. I suggest VS Code. [Download VS Code](https://code.visualstudio.com/Download)

## Summary

HTML and CSS and Javascript documents create a quiz with multiple choice questions with Javascript trivia.
This project emphasizes the use of using Javascript to make dynamic changes to an HMTL document.
This project utilizes the use of appending HTML pages.

![Code-Quiz-Photo](https://github.com/NasGenius/homework-week04/blob/main/assets/Screen%20Shot%202020-11-07%20at%203.10.04%20PM.png)

## This project has the following features:

- A Quiz start button
  - This will be a timed quiz.
  - You will have a total of 75 seconds to complete the quiz.

![Question-Example-Photo](https://github.com/NasGenius/homework-week04/blob/main/assets/Screen%20Shot%202020-11-07%20at%203.10.21%20PM.png)
  
![Answer-Question-Photo](https://github.com/NasGenius/homework-week04/blob/main/assets/Screen%20Shot%202020-11-07%20at%203.10.40%20PM.png)

- An appended HTML page that features questions, and multiple choice answers
  - If questions are answered incorrectly, 5 seconds are deducted off remaining time
  - Answers are recording using an event listener, "click" and tracks correct answers

![Submit-Answers-Photo](https://github.com/NasGenius/homework-week04/blob/main/assets/Screen%20Shot%202020-11-07%20at%203.11.09%20PM.png)

- A Highscores HTML
  - This a list summary of intials and final scores
  - Clear button resets the page and local storage
  - Go back button travels to the start of the quiz

![View-Highscores-Photo](https://github.com/NasGenius/homework-week04/blob/main/assets/Screen%20Shot%202020-11-07%20at%203.11.41%20PM.png)

## Psuedo Code and Project Requirements:

- Create a timer attached to a button with a starting value of 0
- When timer is pressed start a reverse countdown
- Create a 0 for countdown
- When countdown starts, start quiz
- Start Quiz will be on appended page
- Append the question: choices
- When user selects the right answer, textcontent "Correct!"
- When user selects the right answer, textcontent "Wrong!"
- Final score will keep track of how many the user got right
- Left over time will be deducted from final score
- Final Score Appended page
- Captures local storage
- Travels to another HTML
- Retrieved highscores

## This project has script features of:

1. Questions contained in an array variable with objects
2. Variable declaration area
3. An event listener (onclick) that generates time interval
4. A function to render the questions and choices on the page using a for loop
5. An event listener on all list choices
6. A comparison statement to compare correct answers to choices
7. An appended page showing the final stats of the individual user with input area for initials, captures local storage
8. Highscores retreived local storage

## To Execute File:
Open in browser

## Features:
1. Two HTML Pages
  - Index.html
    - Contains landing page to start timer
    - Appends two new pages
2. Highscores * Retreives local data from previous page
3. One CSS Page
  - Styles.css
Contains centering and styling for html list features
Contains media queries
Two Javascript Page * Contains: * Variables, including arrays with object * Event listeners * if/else if statements * For Loops * Functions * Local Storage set and get

## Authors
<b> Billy Gray </b>

## Final Thoughts

I came across some issues with my local environment and I was unable to make as many commits as I normally do. The homework in itself was challenging. Ultimately, I did well with the requirements was given.

## Credits

Credit for this project goes to my instructor @aaronjewell, my TA's along with my fellow peers from Group - 5 for answering questions. They all assist me with my assignment. By posting helpful links, our class lectures and most importantly all the practice that was given. 

## License

MIT License

Copyright (c) [2020] [<b> Billy Gray</b>]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
© 2020 OSU Boot Camp.




