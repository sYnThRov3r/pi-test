# PI Digits Challenge

A web application that tests your knowledge of the digits of PI. How many digits can you remember?

## Features

- Type consecutive digits of PI directly in the display area
- Visual feedback for correct and incorrect digits
- Digits are color-coded:
  - Green: Correct digits
  - Red: Incorrect digits
  - Blue: Revealed digits
- Font color changes every six digits to help with memorization
- Background briefly changes color when you make a mistake
- Must correct any incorrect digit before continuing
- Keeps track of your current streak of correct digits
- Streak is maintained even when you make a wrong guess
- Reset button to start over
- Reveal button to show the next digit(s) if you're stuck
- Configurable number of digits to reveal (1-1000)
- Press Enter in the reveal count input to trigger the reveal
- Revealed digits are added to your streak
- Remembers your last reveal count setting
- Resizable text box that can be adjusted to your preference
- Contains the first 1000 digits of PI (after the decimal point)
- Backspace key to remove the last digit

## How to Run

1. Clone or download this repository
2. Open the `index.html` file in any modern web browser

## How to Use

1. Click on the display area and start typing the digits of PI (after the decimal point, starting with 1, 4, 1, 5...)
2. If you make a mistake, the digit will appear in red, and you must correct it before continuing
3. Set how many digits you want to reveal (1-1000) using the number input next to the Reveal button
4. Press the "Reveal" button or hit Enter in the number input to show the next digit(s) and add them to your streak
5. Use the "Reset" button to start over
6. Notice how the color changes every six digits to help you memorize patterns
7. Resize the text box by dragging the bottom-right corner to adjust the display area

## Keyboard Shortcuts

- `Escape` key: Reset the game
- `Backspace` key: Remove the last digit
- `Enter` key (in reveal count input): Reveal digits

## Technical Details

- Pure HTML, CSS, and JavaScript with no external dependencies
- Contains the first 1000 digits of PI (after the decimal point)
- Responsive design that works on both desktop and mobile devices
- Uses localStorage to remember your reveal count setting

Enjoy testing your PI memory skills! 