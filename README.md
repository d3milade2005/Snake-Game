<header>
  <h1>Snake Game with Python Turtle (OOP)</h1>
</header>

<section>
  <h2>Description</h2>
  <p>This is a classic Snake game built using Python's turtle module. It leverages Object-Oriented Programming (OOP) principles to enhance structure and reusability. The player controls a snake that grows in length as it eats food. The goal is to grow the snake without colliding with walls or itself. The game ends when the snake collides with its own body or the boundaries.</p>

  <p>The game is created with Python's turtle graphics module, providing a simple way to draw the game window, move the snake, and handle collision detection. The OOP design ensures that the game is modular, making it easy to expand or modify for future improvements.</p>

  <h3>Features</h3>
  <ul>
      <li><strong>Snake Movement:</strong> The snake can be controlled using arrow keys (Up, Down, Left, Right).</li>
      <li><strong>Growing Snake:</strong> The snake grows in length as it eats food.</li>
      <li><strong>Game Over:</strong> The game ends when the snake collides with the walls or itself.</li>
      <li><strong>Scoring:</strong> The player's score increases as the snake eats food. The score is displayed on the screen.</li>
      <li><strong>Modular OOP Design:</strong> The game is implemented using classes, making the code cleaner and easier to maintain.</li>
  </ul>

  <h3>Technologies Used</h3>
  <ul>
      <li><strong>Python:</strong> Core programming language.</li>
      <li><strong>Turtle Graphics:</strong> Used for rendering the game interface.</li>
      <li><strong>Object-Oriented Programming (OOP):</strong> Used to structure the code in a maintainable and modular way.</li>
  </ul>

  <h3>Game Controls</h3>
  <ul>
      <li><strong>Up Arrow:</strong> Move the snake up.</li>
      <li><strong>Down Arrow:</strong> Move the snake down.</li>
      <li><strong>Left Arrow:</strong> Move the snake left.</li>
      <li><strong>Right Arrow:</strong> Move the snake right.</li>
  </ul>

  <h3>How It Works</h3>
  <h4>Game Design with OOP</h4>
  <p>The game consists of several classes that represent different components of the game:</p>
  <ul>
      <li><strong>Snake:</strong> Handles the movement and growth of the snake. It stores the snake's body as a list of segments and manages the logic for movement and collision detection.</li>
      <li><strong>Food:</strong> Randomly generates food on the screen for the snake to eat. When the snake collides with the food, it grows.</li>
      <li><strong>Game:</strong> Manages the overall game loop, keeps track of the score, and checks for collisions (snake with food, snake with itself, snake with walls).</li>
      <li><strong>Screen:</strong> Manages the graphical window using the turtle module.</li>
  </ul>
