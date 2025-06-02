# Rock Paper Scissors Game

A simple, interactive Rock Paper Scissors game built with HTML, CSS, and JavaScript where you can play against the computer.

In Japan, "janken" (ジャンケン) refers to the game of Rock Paper Scissors. It's a widely used method for resolving disagreements or determining order in various situations, both formally and informally. The term "janken" is also the name of a specific variation of the sansukumi-ken game, which is the origin of the modern rock paper scissors. 

## 🎮 Features

- **Interactive Gameplay**: Click buttons to make your choice
- **Computer AI**: Computer makes random selections
- **Score Tracking**: Keeps track of wins, losses, and ties
- **Responsive Design**: Works on desktop and mobile devices
- **Clean UI**: Simple and intuitive interface

## 🚀 How to Play

1. Choose your move by clicking one of the three buttons:
   - 🪨 Rock
   - 📄 Paper
   - ✂️ Scissors

2. The computer will automatically make its choice

3. The winner is determined by classic rules:
   - Rock beats Scissors
   - Scissors beats Paper
   - Paper beats Rock
   - Same choices result in a tie

4. Your score updates automatically after each round

## 🛠️ Technologies Used

- **HTML5** - Structure and layout
- **CSS3** - Styling and responsive design
- **JavaScript** - Game logic and interactivity

## 📁 Project Structure

```
janken-js/
├── index.html          # Main HTML file
├── index.js           # Game logic and functionality
├── styles.css         # Styling and layout
└── README.md          # Project documentation
```

## 🎯 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ulricscott/janken-js.git
   ```

2. **Navigate to project directory**
   ```bash
   cd janken-js
   ```

3. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server like Live Server in VS Code

## 🎲 Game Logic

The game implements the standard Rock Paper Scissors rules:

```javascript
// Winning conditions
Rock > Scissors
Scissors > Paper  
Paper > Rock
```

The computer's choice is generated using `Math.random()` to ensure fair and unpredictable gameplay.

## 🔧 Customization

You can easily customize the game by modifying:

- **Styling**: Edit `styles.css` to change colors, fonts, or layout
- **Game Logic**: Modify `index.js` to add new features or rules
- **UI Elements**: Update `index.html` to change button text or add new elements

## 🌟 Future Enhancements

Potential features to add:
- [ ] Best of X rounds mode
- [ ] Difficulty levels for computer AI
- [ ] Sound effects and animations
- [ ] Local storage for persistent scores
- [ ] Multiplayer mode
- [ ] Game statistics and history

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by the classic Rock Paper Scissors game
- Built as a learning project for JavaScript fundamentals

---

**Enjoy playing!** 🎉

*Made with ❤️ and JavaScript*