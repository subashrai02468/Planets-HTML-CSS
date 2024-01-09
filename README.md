# Planets-HTML-CSS

This is a simple HTML and CSS project that demonstrates the animation of planets orbiting around a central "sun". It creates a visual representation of three planets moving in elliptical orbits with unique colors and animation effects.

## How to Use

To view the animation, simply open the `index.html` file in a web browser. You'll see three planets moving around a central "sun" in a circular motion. The planets have different colors and animation styles, showcasing their orbits.

## File Structure

### HTML (`index.html`)

The HTML file contains the structure of the planets' orbits and their animations. It includes the following main elements:

- `planets-container`: A container for the planetary system.
- `sun`: Represents the central star.
- `planet-index`: Contains each individual planet's orbit path and container.
- `planet-container`: Holds the individual planet and controls its animation.
- `planet`: Represents each planet in the system.

### CSS (`styles.css`)

The CSS file contains styles and animations for the planetary system. Key elements of the CSS include:

- Styling for the overall layout, including the background color and container sizes.
- Animation keyframes (`@keyframes`) defining the movement and appearance changes for each planet's orbit.
- Individual planet styles, including colors, sizes, and animation sequences.

## Animation Logic

- The planets' movements are controlled through CSS animations using `@keyframes`.
- Each planet has its unique animation sequence, controlling its orbit, rotation, and color change effects.
- The `hideFirstPlanet`, `hideSecondPlanet`, and `hideThirdPlanet` animations control the visibility and scaling of the planets.

## Contribution

Feel free to contribute to this project by enhancing the animation effects, adding more planets, or improving the overall design.

## License

This project is licensed under the [MIT License](LICENSE).
