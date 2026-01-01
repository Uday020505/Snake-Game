# 🐍 Snake Game

A classic Snake game implementation built with Python and Pygame.

## 📋 Description

This is a traditional Snake game where you control a snake that grows longer as it eats food. The goal is to eat as much food as possible without hitting the walls or your own body. Each piece of food eaten increases your score by 1.

## 🎮 Features

- Classic snake gameplay mechanics
- Score tracking system
- Smooth snake movement
- Collision detection (walls and self)
- Randomized food placement
- Grass-patterned game board
- Clean and simple UI

## 🔧 Requirements

- Python 3.x
- Pygame library

## 📦 Installation

1. Make sure you have Python installed on your system
2. Install Pygame using pip:

```bash
pip install pygame
```

3. Download the game file
4. Run the game:

```bash
python snake_game.py
```

## 🕹️ How to Play

### Controls
- **↑ (Up Arrow)** - Move snake up
- **↓ (Down Arrow)** - Move snake down
- **← (Left Arrow)** - Move snake left  
- **→ (Right Arrow)** - Move snake right

### Rules
1. Control the snake to eat the red food blocks
2. Each food item eaten makes the snake grow longer and increases your score
3. Avoid hitting the walls
4. Avoid running into your own body
5. The game ends when you collide with a wall or yourself

## 🎯 Game Settings

- **Window Size:** 800x600 pixels
- **Cell Size:** 20x20 pixels
- **Game Speed:** Updates every 150ms
- **Starting Length:** 3 blocks
- **Colors:**
  - Snake: Dark Green
  - Food: Red
  - Background: Light Green
  - Grass Pattern: Yellow-Green
  - Score Text: White

## 🎨 Game Board

The game features a checkered grass pattern background for a more visually appealing playing field.

## 📊 Scoring

- Each food item eaten: +1 point
- Score is displayed in the top-right corner of the screen

## 🛑 Game Over

The game ends immediately when:
- The snake hits any wall
- The snake collides with its own body

After game over, the program exits automatically.

## 🔮 Future Enhancements (Ideas)

- Add a game over screen with final score
- Implement restart functionality
- Add difficulty levels (speed variations)
- Include high score tracking
- Add sound effects
- Implement pause functionality
- Add different game modes

## 📝 License

This is a learning project and is free to use and modify.

## 🤝 Contributing

Feel free to fork this project and add your own improvements!

---

**Enjoy the game! 🐍🎮**
