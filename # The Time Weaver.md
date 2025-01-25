# The Time Weaver

**The Time Weaver** is an interactive web game where players can navigate through the past, present, and future to influence the development of a city. The objective is to plant a tree, build a reservoir, and construct a city to stabilize the future. The game features a 3D environment built with Three.js, interactive buttons, and fun visual effects like floating particles and confetti.

## Features

1. **Timeline Navigation**: Players can switch between different time periods—past, present, and future—by clicking the corresponding buttons. Actions in the past affect the present and future.
2. **Interactive Actions**:
   - In the **past**, players can plant a tree or build a reservoir.
   - In the **present**, players can observe the effects of their past actions or construct a city.
   - In the **future**, players must stabilize the city by using their past decisions.
3. **3D Visuals**: A basic 3D scene is created with Three.js to represent the environment. A floating particle effect is used to enhance the visual appeal.
4. **Celebration**: If the city is stabilized, a confetti effect is triggered to celebrate the success.

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the layout, with animations and visual effects.
- **JavaScript**: For handling interactions, controlling the game logic, and integrating 3D rendering with Three.js.
- **Three.js**: A 3D JavaScript library used to render the environment and objects.
- **Canvas Confetti**: A JavaScript library used for creating confetti effects.

## How It Works

### 1. Setting up the Timeline
The game starts with three buttons: **Past**, **Present**, and **Future**. Clicking each button navigates the player to the respective time period. 

- **Past**: The player can plant a tree or build a reservoir.
- **Present**: The effects of actions taken in the past are shown, and the player can build a city or see the state of the environment.
- **Future**: The player is tasked with stabilizing the city. If the city is stabilized, a celebration with confetti is triggered.

### 2. Actions and Their Effects
- **Planting a Tree**: A tree object is created in the 3D scene. It symbolizes the environmental impact on the future.
- **Building a Reservoir**: A reservoir is created, and its availability improves the water resources in the present.
- **Building a City**: A simple 3D city building appears.
- **Stabilizing the City**: Once a tree and reservoir are built, the player can stabilize the city by using these resources. If successful, the future city thrives, and a celebration is triggered.

### 3. Particle Effect and Confetti
Floating particles are created at random intervals, and a confetti animation is triggered when the player successfully stabilizes the city.

## Setup and Usage

To run this project:

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Use the buttons to navigate between time periods and take actions.

### Requirements

- A modern web browser (Chrome, Firefox, etc.)
- Internet connection (to load Three.js and Canvas Confetti from CDN)

## Customization

You can modify the visual effects, 3D models, and particle behavior by adjusting the Three.js scene setup or the `confetti()` function in the JavaScript code. You can also change the background city image or customize the text shown during each time period.

## Credits

- **Three.js**: [https://threejs.org](https://threejs.org)
- **Canvas Confetti**: [https://www.npmjs.com/package/canvas-confetti](https://www.npmjs.com/package/canvas-confetti)

## License

This project is open-source and available under the MIT License.

