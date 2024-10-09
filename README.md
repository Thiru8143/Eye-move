# Eye-Tracking Animation

This project creates an interactive animation where two eyes follow the movement of the user's mouse pointer across the screen.

## Technologies Used
- **HTML5**: To structure the webpage.
- **CSS**: For styling the eyes and positioning them in the browser window.
- **JavaScript**: For handling mouse movement and updating the position of the eyeballs.

## Features
- The eyes move in sync with the user's mouse cursor, creating a fun, interactive effect.
- Two circular eyes with dark eyeballs are centered on the page.
- The eyes follow the cursor movement by updating their position based on the mouse's coordinates.

## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in any modern browser.
3. Move your mouse across the screen, and watch as the eyes follow your cursor!

## Code Breakdown

- **HTML**: 
  - The webpage contains two `div` elements representing the eyes. Each eye has a smaller `div` inside it for the eyeball.

- **CSS**: 
  - The eyes and eyeballs are styled with a circular shape using `border-radius`.
  - The eyes are positioned centrally at the bottom of the screen using Flexbox.

- **JavaScript**: 
  - The `move()` function is triggered by the `onmousemove` event, tracking the mouse's position.
  - The position of each eyeball is updated relative to the mouse's movement using the `transform` property to create the effect of the eyeballs following the cursor.

## Installation
No installation required. Simply open the `index.html` file in a browser to view the interactive animation.

## Future Enhancements
- Add additional styling for the eyes to enhance the design.
- Allow the size of the eyes and eyeballs to change based on the distance from the cursor.
- Introduce more interactivity, such as blinking or changing colors when the mouse hovers over the eyes.

## License
This project is open-source and available under the MIT License.
