# Clock Angle Calculator

## Description
The **Clock Angle Calculator** is a simple web application that calculates the angle between the hour and minute hands of an analog clock based on user input. It provides precise degree measurements between the hands for any given time in **HH:MM** format.

## Features
- Accepts time input in **HH:MM** format.
- Calculates the angles of the **hour hand** and **minute hand** from 12:00.
- Computes the **smallest angle** between the clock hands.
- Displays results instantly on the webpage.
- Simple and user-friendly interface.

## How It Works
1. Enter the time in the **HH:MM** format in the input field.
2. Click the **Calculate** button.
3. The script processes the input and calculates:
   - **Hour Hand Angle** from 12:00.
   - **Minute Hand Angle** from 12:00.
   - **Angle Between the Hands** (smallest angle).
4. The results are displayed below the button.

## Calculation Formula
- **Minute Hand Angle** = `(Minutes / 60) * 360`
- **Hour Hand Angle** = `(Hours % 12) * (360 / 12) + (Minutes / 60) * (360 / 12)`
- **Angle Difference** = `|Hour Angle - Minute Angle|`
- **Smallest Angle** = `Min(Angle Difference, 360 - Angle Difference)`

## Technologies Used
- **HTML** – For structuring the page.
- **CSS** – For basic styling.
- **JavaScript** – For calculating and displaying the angles.

## Usage
1. Open the `index.html` file in a browser.
2. Input a valid time (e.g., `03:15` for 3:15 AM/PM).
3. Click **Calculate** to get the results.
4. The output displays:
   - Hour hand angle
   - Minute hand angle
   - Angle between the hands

## Example Calculation
For `03:15`:
- **Minute Hand Angle** = `(15 / 60) * 360 = 90°`
- **Hour Hand Angle** = `(3 * 30) + (15 / 60) * 30 = 97.5°`
- **Angle Between Hands** = `|97.5 - 90| = 7.5°`

## Live Demo
If hosted, add a link here: `https://promauriya.github.io/clock-hour-minute-hand-angle/`

## Author
Developed by **Ryan Mahato**

## License
This project is licensed under the MIT License.

