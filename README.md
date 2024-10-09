# Bouncing Balls Simulation

A simple web project that simulates multiple bouncing balls inside a container using HTML, CSS, and JavaScript. The balls move with random initial velocities and interact with the container’s walls, bouncing off them while being affected by gravity.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Multiple balls with random initial velocities and colors.
- Simulates gravity for realistic ball movement.
- Balls bounce off the container walls.
- Smooth animation using `requestAnimationFrame`.
- Adjustable gravity and bounce behavior.

## How It Works

This project demonstrates basic physics concepts (gravity and bouncing) using JavaScript:
- **HTML** defines the structure of the page, with a container to hold the balls.
- **CSS** styles the container and the balls.
- **JavaScript** handles the ball movement by calculating new positions on each frame and applying gravity and velocity changes.

### Main Concepts
- **Gravity** is simulated by increasing the vertical velocity (`y_vel`) over time.
- **Bouncing** is implemented by reversing the velocity when the ball hits the container boundaries, reducing speed on bounce with a bounce factor.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/bouncing-balls-simulation.git
   cd bouncing-balls-simulation
   open index.html
## Usage
You can modify the simulation by adjusting the following values in the JavaScript file:

Number of Balls: Change the for loop limit in the ballCount() function to increase/decrease the number of balls.
Gravity: Modify the gravity variable to make the balls fall faster or slower.
Bounce Factor: Adjust the bounceFactor to control how much energy the balls retain after bouncing.

