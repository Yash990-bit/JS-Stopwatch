# Stopwatch Project

This is a simple Stopwatch web application built using HTML, CSS, and JavaScript. It allows users to start, stop, and reset a timer. The stopwatch displays minutes, seconds, and hundredths of a second (tens) on the screen. The background has an animation effect and an image for a sleek look and feel.

## Features

- **Start, Stop, and Reset**: Control the timer with the respective buttons.
- **Responsive Design**: The layout adjusts based on screen size, ensuring a great experience on both mobile and desktop devices.
- **Animated Background**: The background has a smooth up-and-down animation to keep the page lively.
- **Timer Display**: The stopwatch displays the time in `MM:SS:TT` format, where `TT` represents hundredths of a second.
  
## Technologies Used

- **HTML5**: For the basic structure of the webpage.
- **CSS3**: To style the page and create animations for the timer and background.
- **JavaScript**: For the stopwatch functionality, including start, stop, and reset actions.
- **Font Awesome (optional)**: For additional icons if you decide to expand the project.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Yash990-bit/JS-Stopwatch
    ```


## Folder Structure


## How It Works

1. **HTML (index.html)**: 
    - The layout consists of a `div` container holding the timer display and buttons (Start, Stop, and Reset).
    
2. **CSS (style.css)**: 
    - The CSS styles the timer and buttons, provides the background image, and adds animations for the timer and page.
    
3. **JavaScript (script.js)**: 
    - The JavaScript controls the stopwatch functionality. The `startTimer` function updates the timer every 10 milliseconds, the `startBtn` starts the timer, the `stopBtn` pauses it, and the `resetBtn` resets the timer.

### Key Functions:
- `startTimer`: Handles the logic of increasing the `tens`, `seconds`, and `minutes`.
- `startBtn.onclick`: Starts the stopwatch.
- `stopBtn.onclick`: Stops the stopwatch.
- `resetBtn.onclick`: Resets the timer to `00:00:00`.

## Demo

Here is a live demo of the stopwatch:

[(https://illustrious-cheesecake-5084db.netlify.app/)]




