# Cloud Typing Game ✈️☁️

An engaging browser-based typing game where you control an aircraft that shoots down clouds by typing words correctly. Improve your typing speed while having fun!

![Game Preview](https://img.shields.io/badge/Type-to%20Shoot-orange) ![Version](https://img.shields.io/badge/version-1.0.0-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🎮 Game Features

- **Interactive Gameplay**: Control a top-down aircraft that automatically fires at clouds when you type matching words
- **Visual Feedback**: Real-time targeting system with glowing effects and bullet animations
- **Hidden Input System**: Type naturally without seeing a text box - your typing appears in a styled display
- **Progressive Difficulty**: Three difficulty levels (Easy, Medium, Hard) with varying cloud speeds
- **Performance Tracking**: Real-time WPM (Words Per Minute) counter and timer
- **Custom Word Lists**: Add your own word lists for personalized practice
- **Sound Effects**: Audio feedback for successful hits and damage
- **High Score System**: Track your best performance with local storage

## 🚀 Live Demo

You can play the game by opening the `index.html` file in any modern web browser. No installation required!

## 📋 How to Play

1. **Start the Game**: Click the "Play Game" button to begin
2. **Type to Shoot**: Start typing any word you see on the clouds
   - As you type, your aircraft will automatically fire at matching clouds
   - The targeted cloud will glow orange
   - A targeting line shows which cloud you're attacking
3. **Complete Words**: Press `Spacebar` after typing a complete word to destroy the cloud
   - An explosion effect confirms the hit
   - Your WPM score updates in real-time
4. **Avoid Collisions**: Clouds that reach your aircraft will damage it
   - You have 100 health points
   - Each collision reduces health by 15 points
5. **Game Over**: When health reaches 0, see your final score and high score

## ⚙️ Configuration Options

### Difficulty Levels
- **Easy**: Slower cloud movement, more time between spawns
- **Medium**: Balanced gameplay (default)
- **Hard**: Faster clouds, frequent spawning

### Custom Word Lists
1. Click "Settings" during gameplay
2. Select "Custom" from the Word List dropdown
3. Enter your words separated by:
   - Commas (,)
   - Spaces
   - Newlines
   - Periods (.)
   - Semicolons (;)
4. Minimum 10 words required

### Sound Settings
Toggle sound effects on/off in the settings menu

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For game rendering
- **Vanilla JavaScript**: No external dependencies
- **CSS3**: Modern styling with animations
- **Web Audio API**: For sound generation

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser supporting HTML5 Canvas

### Performance
- Smooth 60 FPS gameplay
- Optimized collision detection
- Efficient particle system for bullets

## 📁 File Structure

```
cloud-typing-game/
│
├── index.html          # Main game file (all-in-one)
├── README.md          # This documentation
└── LICENSE            # MIT License
```

## 🎯 Game Mechanics

### Scoring System
- **WPM Calculation**: Words typed per minute based on actual time elapsed
- **Real-time Updates**: Score updates continuously during gameplay
- **High Score**: Persisted using browser's localStorage

### Cloud Behavior
- Clouds spawn from the top of the screen
- Each cloud contains a random word from the word list
- Cloud speed increases with difficulty level
- Clouds have collision detection with the aircraft

### Aircraft Controls
- Automatic horizontal movement
- Fires bullets when typing matches a cloud's word
- Top-down view with realistic aircraft design
- Shadow effect for depth perception

### Firing System
1. **Auto-fire**: Bullets fire continuously while typing correct letters
2. **Smart Targeting**: Only fires at clouds matching your input
3. **Visual Effects**: 
   - Orange glow on targeted clouds
   - Bullet trails with golden effects
   - Explosion animation on destruction
4. **Audio Feedback**: Different sounds for firing and impacts

## 👨‍💻 Developer Information

**Developer**: Abhijit  
*"Keep typing, keep improving!"*  
**Contact**: [WhatsApp](https://wa.me/919000000000)

## 🔧 Customization Guide

### Modifying Game Settings

To adjust game parameters, edit these variables in the JavaScript section:

```javascript
// Cloud spawn rate (frames between spawns)
cloudSpawnInterval = 120; // Lower = more frequent

// Character movement speed
characterSpeed = 2; // Higher = faster movement

// Damage per collision
updateHealth(health - 15); // Change 15 to adjust damage

// Bullet firing rate
firingInterval = setInterval(..., 150); // Change 150ms for fire rate
```

### Adding New Features

The game is built with modularity in mind. Key classes:
- `Cloud`: Manages cloud objects
- `Bullet`: Handles projectile physics
- `character`: Aircraft rendering and properties

## 📈 Future Enhancements

- [ ] Power-ups (rapid fire, slow motion, etc.)
- [ ] Multiple aircraft skins
- [ ] Leaderboard system
- [ ] Multiplayer support
- [ ] Mobile touch keyboard support
- [ ] Achievement system
- [ ] Background music
- [ ] Weather effects

## 🐛 Known Issues

- On some browsers, the first sound might have a slight delay
- Custom word lists must contain only alphabetic characters
- Game requires keyboard input (no mobile support currently)

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Abhijit

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Inspired by classic typing games
- Built with passion for improving typing skills
- Special thanks to all future contributors

---

**Happy Typing!** ✈️☁️💨
