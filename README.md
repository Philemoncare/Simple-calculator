# Advanced Smart Calculator

A feature-rich, intelligent calculator application with advanced mathematical operations, history tracking, and a beautiful user interface.

## Features

- **Basic Operations**: Addition, subtraction, multiplication, division
- **Advanced Functions**: 
  - Trigonometric functions (sin, cos, tan, asin, acos, atan)
  - Logarithmic functions (log, ln)
  - Power and root operations (x², x³, √x, ∛x)
  - Factorial, permutations, combinations
  - Percentage calculations
- **History Tracking**: Complete calculation history with timestamps
- **Variable Storage**: Store and recall variables
- **Unit Conversions**: Temperature, length, weight, volume
- **Graphing**: Plot mathematical functions
- **Keyboard Support**: Full keyboard input support
- **Dark/Light Theme**: User preference theme switching
- **Responsive Design**: Works on desktop and mobile devices

## Project Structure

```
Simple-calculator/
├── index.html           # Main HTML structure
├── css/
│   ├── style.css        # Main stylesheet
│   └── themes.css       # Theme styles
├── js/
│   ├── app.js           # Main application logic
│   ├── calculator.js    # Calculator engine
│   ├── ui.js            # UI management
│   ├── history.js       # History management
│   └── utils.js         # Utility functions
├── assets/
│   ├── icons/           # Application icons
│   └── screenshots/     # Documentation screenshots
├── package.json         # Node dependencies
├── webpack.config.js    # Build configuration
└── README.md            # This file
```

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

Opens the calculator at `http://localhost:8080`

### Production Build

```bash
npm run build
```

### Testing

```bash
npm test
```

## Technology Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Build Tool**: Webpack
- **Testing**: Jest
- **Package Manager**: npm

## Usage

1. Enter numbers and operations using the buttons or keyboard
2. Press "=" or Enter to calculate
3. View your calculation history in the side panel
4. Store variables for later use
5. Convert units with the conversion tools
6. Plot functions with the graphing feature

## Keyboard Shortcuts

- `0-9`: Number input
- `+`, `-`, `*`, `/`: Operations
- `Enter` or `=`: Calculate
- `C`: Clear
- `DEL` or `Backspace`: Delete last digit
- `h`: Show history
- `v`: Show variables
- `t`: Toggle theme
- `u`: Show unit converter
- `g`: Show graphing tool

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see LICENSE file for details

## Support

For issues or feature requests, please open an issue on GitHub.
