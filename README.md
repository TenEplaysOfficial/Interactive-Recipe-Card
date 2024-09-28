
# Interactive Recipe Card

## Overview
This Recipe App allows users to view, prepare, and cook various recipes. The app features a user-friendly interface with a popup display for each recipe, including ingredients, steps, and a countdown timer for preparation time.

## Technologies Used
- **HTML**: Used for structuring the webpage, creating elements like headings, lists, buttons, and popups.
- **CSS**: Used for styling the app, creating responsive designs, and enhancing user experience with transitions and hover effects.
- **JavaScript**: Used for the interactive functionalities, such as displaying recipe details, managing the countdown timer, and handling user interactions.

## Code Concepts

### Recipe Data Structure
The recipes are stored in a JavaScript object named `recipes`, where each key represents a recipe. Each recipe object contains the following properties:
- `title`: The name of the recipe.
- `description`: A brief description of the dish.
- `ingredients`: An array of ingredients required for the recipe.
- `steps`: An array of instructions detailing how to prepare the dish.
- `prepTime`: The preparation time in minutes.

### Opening and Closing Popups
The `openPopup` function retrieves the selected recipe's details and populates the popup with the title, description, ingredients, and cooking steps. The popup is displayed by setting the `display` style of the `popupBg` element to `block`.

To close the popup, the `closePopup` function is invoked, which hides the popup and clears any running countdown.

### Countdown Timer
The app features a countdown timer that starts when the user begins cooking. The `startCooking` function initializes the countdown based on the recipe's preparation time, converting minutes to seconds. The timer updates every second, and the countdown element's text changes to reflect the time left. If the time reaches zero, an alert is displayed to notify the user that the cooking time is up.

### Responsive Design
The CSS is structured to ensure the app is responsive across different devices. The use of CSS Grid for the recipe layout allows for a flexible and organized display of recipe cards. Media queries are implemented to adjust styles based on screen size, ensuring an optimal viewing experience on mobile devices.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/TenEplaysOfficial/Interactive-Recipe-Card.git
   ```
2. Open `index.html` in a web browser.

## Usage
Click on any recipe card to view its details. Start cooking by clicking the "Start Cooking" button, which will initiate the countdown timer for preparation time.

## License
This project is licensed under the MIT License.

![Screenshot 1](<img/Screenshot.png>)


*Stay connected! Follow me on [Socials](https://linktr.ee/tenegames).*
