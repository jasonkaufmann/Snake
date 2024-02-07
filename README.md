# Snake Game in Unity

This Snake game is a modern take on the classic arcade game. Developed with Unity and C#, it features smooth gameplay, simple controls, and a scoring system. As you navigate the snake around the screen, eating food to grow, you must avoid colliding with yourself and the game area's borders.

## Features

- **Smooth Snake Movement:** Control the snake as it moves across the game area.
- **Score Tracking:** Your score increases each time the snake eats food.
- **Increasing Difficulty:** The game speeds up as the snake grows, increasing the challenge.
- **Simple Controls:** Use the arrow keys to change the snake's direction.

## Getting Started

### Prerequisites

- Unity 2020.3 or later.
- A code editor such as Visual Studio.

### Installation

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/jasonkaufmann/Snake.git
   
### Open the project in Unity:

- Launch Unity Hub.
- Click on 'Add' and select the cloned project directory.
- Select the project from the list to open it in Unity.
- After Unity loads the project, navigate to the `Scenes` folder and open the main scene to start editing or playing the game.

### Controls

- **Up Arrow Key:** Move Up
- **Down Arrow Key:** Move Down
- **Left Arrow Key:** Move Left
- **Right Arrow Key:** Move Right

### How to Play

- Start the game by pressing the Play button in Unity or by building and running the game executable.
- Use the arrow keys to control the direction of the snake.
- Eat the red food that appears randomly on the screen to grow the snake and gain points.
- Avoid colliding with the walls or the snake itself.
- Try to score as high as possible before the game ends.

### Building the Game

To build the game for your desired platform, follow these steps:

1. Go to `File > Build Settings` in Unity.
2. Select your target platform from the list.
3. Click on `Build` and choose where to save the built game.
4. Follow the prompts to complete the build process.

### Customization

You can customize the game by modifying the public variables in the `Snake` script, such as:

- `newMaterialRef`: Change the material of the snake for different looks.
- `cam`: Adjust the camera settings to change the view.
- `scoreTextObj`: Modify the UI Text object to display scores differently.

Feel free to explore and tweak other settings in the Unity Editor to personalize the game further.

### Contributing

Contributions are welcome! If you have ideas for improvements or bug fixes, please feel free to fork the repository, make your changes, and submit a pull request.

### License

Distributed under the MIT License. See `LICENSE` for more information.
