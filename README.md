# Tennis Ball Bounce Game

A mobile-friendly Flappy Bird clone with a tennis theme! Control a tennis ball and navigate through tennis court nets by tapping to hit the ball with your racket.

## 🎾 Game Overview

Tennis Ball Bounce is a simple, addictive arcade game where you guide a tennis ball through gaps in tennis nets. Each successful pass scores a point. The game features smooth animations, including a realistic tennis racket swing animation when you tap the screen.

## 🎮 How to Play

1. **Start the Game**: Click or tap the "Start Game" button on the welcome screen
2. **Control the Ball**: Tap anywhere on the screen to make your tennis racket hit the ball upward
3. **Navigate Obstacles**: Fly through the gaps between the tennis nets
4. **Score Points**: Each net you successfully pass through earns you one point
5. **Avoid Collisions**: Don't hit the nets or the ground, or it's game over!

## ✨ Features

- **Tennis-Themed Graphics**
  - Yellow tennis ball with authentic curved line details
  - Oval-shaped tennis racket with string pattern
  - Tennis court nets with realistic grid pattern
  - Green tennis court surface with white boundary lines
  - Animated clouds in the sky

- **Smooth Animations**
  - Tennis racket swing animation when you tap
  - Ball squash effect on impact
  - Fluid ball movement with realistic physics

- **Mobile-Optimized**
  - Touch-friendly controls
  - Responsive design that adapts to any screen size
  - Prevents page scrolling during gameplay

- **Game Progression**
  - Start screen with instructions
  - Live score display during gameplay
  - Game over screen with final score
  - Quick restart option

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For all game rendering and animations
- **JavaScript**: Game logic, physics, and animation loops
- **CSS3**: UI styling and responsive layout

### Game Mechanics
- Gravity system for realistic ball physics
- Collision detection for obstacles and boundaries
- Procedural obstacle generation
- Score tracking system
- Animation frame management

### Browser Compatibility
The game works on all modern browsers that support HTML5 Canvas:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Installation & Setup

### Option 1: Direct Use
Simply open the HTML file in any modern web browser. No installation required!

### Option 2: Local Server (Optional)
For development or testing:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## 🎯 Game Controls

- **Desktop**: Click with mouse
- **Mobile/Tablet**: Tap on screen
- **Goal**: Time your taps to keep the ball bouncing through the gaps

## 🏆 Gameplay Tips

1. **Timing is Everything**: Don't tap too rapidly - let the ball fall a bit before hitting again
2. **Aim for the Center**: Try to fly through the middle of the gap for maximum safety margin
3. **Stay Calm**: The game gets faster as you progress, but panicking leads to mistakes
4. **Practice Makes Perfect**: Each playthrough helps you understand the ball physics better

## 🎨 Customization

The game is highly customizable. You can easily modify:

- **Ball physics**: Adjust `gravity`, `jump`, and `speed` variables
- **Colors**: Change ball color, court color, net appearance
- **Difficulty**: Modify `racquetGap` for easier/harder gameplay
- **Obstacle spacing**: Adjust `racquetSpacing` for more/less frequent obstacles

## 📊 Game Statistics

- **Obstacle Gap**: 150 pixels
- **Obstacle Spacing**: 300 pixels
- **Ball Radius**: 15 pixels
- **Gravity**: 0.5
- **Jump Force**: -8
- **Game Speed**: 3 pixels per frame

## 🐛 Known Issues

- Screen rotation during gameplay will reset the game
- Very small screens (< 320px width) may have difficulty displaying all elements

## 🔮 Future Enhancements

Potential features for future versions:
- High score tracking with local storage
- Difficulty levels (easy, medium, hard)
- Sound effects and background music
- Power-ups (slow motion, shield, double points)
- Different ball skins and racket designs
- Multiplayer mode
- Leaderboards

## 📄 License

This game is free to use and modify for personal and educational purposes.

## 🤝 Contributing

Feel free to fork this project and add your own features! Some ideas:
- Add sound effects
- Implement difficulty progression
- Create different themes (grass court, clay court, hard court)
- Add particle effects on ball hits

## 👨‍💻 Developer Notes

### Code Structure
- **Game Loop**: Uses `requestAnimationFrame` for smooth 60 FPS rendering
- **State Management**: Simple boolean flags for game states
- **Collision Detection**: Rectangle-based collision for nets, circle-point for ground
- **Animation System**: Frame-based animation for racket swing effect

### Performance Considerations
- Efficient canvas clearing and redrawing
- Minimal DOM manipulation during gameplay
- Optimized collision detection
- Object pooling for obstacles

## 🎮 Have Fun!

Enjoy playing Tennis Ball Bounce! Try to beat your high score and challenge your friends. Remember: in tennis and in this game, practice makes perfect!

---

Made with ❤️ for tennis and arcade game enthusiasts!