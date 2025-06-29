# Contributing to Cloud Typing Game

First off, thank you for considering contributing to Cloud Typing Game! It's people like you that make this game better for everyone.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps to reproduce the problem**
* **Provide specific examples**
* **Describe the behavior you observed and what behavior you expected**
* **Include screenshots if possible**
* **Include browser information**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a detailed description of the suggested enhancement**
* **Provide specific examples to demonstrate the enhancement**
* **Describe the current behavior and expected behavior**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Do not include issue numbers in the PR title
* Follow the JavaScript styleguide
* Include thoughtfully-worded, well-structured commit messages
* Update documentation for any changed functionality
* End all files with a newline

## Styleguides

### JavaScript Styleguide

* Use 4 spaces for indentation
* Use camelCase for variable and function names
* Use PascalCase for class names
* Add comments for complex logic
* Keep functions small and focused
* Use meaningful variable names

Example:
```javascript
// Good
function calculateBulletTrajectory(startX, startY, targetX, targetY) {
    const deltaX = targetX - startX;
    const deltaY = targetY - startY;
    // ... rest of the function
}

// Bad
function calc(x1, y1, x2, y2) {
    const dx = x2 - x1;
    const dy = y2 - y1;
    // ... rest of the function
}
```

### Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### Documentation Styleguide

* Use Markdown for documentation
* Reference functions and classes in backticks: \`functionName()\`
* Include code examples where helpful
* Keep explanations clear and concise

## Project Structure

```
cloud-typing-game/
├── index.html          # Main game file
├── README.md          # Project documentation
├── CONTRIBUTING.md    # Contribution guidelines
└── LICENSE            # MIT License
```

## Setting Up Development Environment

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/cloud-typing-game.git`
3. Create a branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Test thoroughly in multiple browsers
6. Commit your changes: `git commit -m "Add your feature"`
7. Push to your fork: `git push origin feature/your-feature-name`
8. Create a Pull Request

## Testing

Before submitting a pull request, please test:

1. **Functionality**: Ensure all game features work as expected
2. **Performance**: Check that the game runs smoothly at 60 FPS
3. **Browser Compatibility**: Test in Chrome, Firefox, Safari, and Edge
4. **Responsive Design**: Verify the game works on different screen sizes
5. **Custom Words**: Test custom word list functionality
6. **Sound Effects**: Ensure audio works properly

## Questions?

Feel free to contact the developer Abhijit via [WhatsApp](https://wa.me/919000000000) if you have any questions.