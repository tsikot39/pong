# Pong Game

## Description

This is a classic Pong game implementation built with vanilla JavaScript and HTML5 Canvas. It recreates the iconic 1972 arcade game where a player controls a paddle to bounce a ball back and forth against a computer opponent. The game features smooth animations, responsive controls, and an adaptive AI opponent that becomes more challenging as the game progresses.

## What It Does

The Pong game allows a single player to compete against an AI-controlled computer opponent in a fast-paced paddle ball game. The objective is to score points by making the ball pass the opponent's paddle while defending your own side. The first player (human or computer) to reach 7 points wins the game.

### Key Gameplay Mechanics:
- **Player Control**: Mouse movement controls the bottom paddle
- **AI Opponent**: Computer-controlled top paddle with adaptive difficulty
- **Ball Physics**: Realistic ball movement with collision detection
- **Dynamic Speed**: Ball speed increases when hit by moving paddles
- **Score Tracking**: First to 7 points wins
- **Game Over Screen**: Shows winner and restart option

## Technologies Used

### Core Technologies:
- **HTML5**: Basic structure and Canvas element
- **CSS3**: Styling, responsive design, and animations
- **Vanilla JavaScript**: Game logic, physics, and rendering
- **HTML5 Canvas API**: 2D graphics rendering and animation

### Browser APIs:
- **Canvas 2D Rendering Context**: For drawing game elements
- **requestAnimationFrame**: Smooth 60fps animation loop
- **Mouse Events**: Player input handling
- **Media Queries**: Responsive design detection

## Features

### 🎮 Core Game Features
- **Classic Pong Gameplay**: Authentic recreation of the original game
- **Single Player Mode**: Play against an intelligent AI opponent
- **Mouse Controls**: Smooth paddle movement following mouse cursor
- **Real-time Physics**: Ball collision detection with paddles and walls
- **Score System**: First to 7 points wins the match
- **Game Over Screen**: Victory display with restart functionality

### 🤖 AI & Difficulty
- **Adaptive AI**: Computer paddle follows ball movement intelligently
- **Dynamic Difficulty**: AI speed increases as ball speed increases
- **Responsive Computer Player**: AI reacts to player movement patterns

### ⚡ Performance & Physics
- **Smooth Animation**: 60fps gameplay using requestAnimationFrame
- **Ball Physics**: Realistic bouncing with trajectory calculation
- **Speed Variation**: Ball speed increases when hit by moving paddles
- **Maximum Speed Limits**: Prevents game from becoming unplayable
- **Collision Detection**: Precise boundary detection for paddles and walls

### 📱 Responsive Design
- **Mobile Optimization**: Adjusted physics for mobile devices
- **Screen Size Adaptation**: Different settings for various screen sizes
- **Cross-device Compatibility**: Works on desktop and mobile browsers
- **Responsive Canvas**: Adapts to different screen resolutions

### 🎨 Visual Design
- **Retro Aesthetic**: Classic black and white color scheme
- **Clean Interface**: Minimalist design focusing on gameplay
- **Dashed Center Line**: Visual separation of play areas
- **Score Display**: Real-time score tracking on screen
- **Game Over Overlay**: Styled victory screen with restart button

### 🎯 User Experience
- **Instant Start**: Game begins immediately on page load
- **Intuitive Controls**: Simple mouse movement for paddle control
- **Visual Feedback**: Paddle contact affects ball trajectory
- **Restart Functionality**: Easy game restart after completion
- **Cursor Management**: Hides cursor during gameplay for immersion

## File Structure

```
pong/
├── index.html          # Main HTML structure
├── script.js           # Game logic and physics
├── style.css          # Styling and responsive design
├── favicon.png        # Browser tab icon
└── README.md          # This documentation
```

## Game Controls

- **Mouse Movement**: Control the bottom paddle by moving your mouse left and right
- **Click "Play Again"**: Restart the game after it ends

## Game Rules

1. Use your mouse to control the bottom paddle
2. Keep the ball from passing your paddle
3. Try to make the ball pass the computer's paddle (top)
4. Each time the ball passes a paddle, the opponent scores a point
5. First player to reach 7 points wins the game
6. Ball speed increases when hit by a moving paddle
7. Ball trajectory changes based on where it hits the paddle

## Technical Implementation Details

### Canvas Setup
- Canvas dimensions: 500px × 700px
- Centered positioning with responsive adjustments
- 2D rendering context for all graphics

### Game Physics
- Ball radius: 5px
- Paddle dimensions: 50px × 10px
- Variable speed system based on device type
- Trajectory calculation using paddle contact position

### Performance Optimizations
- Uses requestAnimationFrame for smooth animation
- Efficient collision detection algorithms
- Mobile-specific performance adjustments
- Minimal DOM manipulation during gameplay

## Browser Compatibility

This game works in all modern browsers that support:
- HTML5 Canvas
- ES6 JavaScript features
- CSS3 media queries
- Mouse event handling

Tested and compatible with:
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Getting Started

1. Open `index.html` in a web browser
2. The game starts automatically
3. Move your mouse to control the bottom paddle
4. Try to score 7 points before the computer does!

## Future Enhancement Ideas

- Touch controls for mobile devices
- Multiplayer support (two human players)
- Different difficulty levels
- Sound effects and background music
- Power-ups and special abilities
- Tournament mode
- High score tracking
- Custom paddle and ball skins
