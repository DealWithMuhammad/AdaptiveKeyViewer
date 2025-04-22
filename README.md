# AdaptiveKeyViewer

AdaptiveKeyViewer is a lightweight utility that displays keyboard inputs on your screen in real-time, with text that automatically adapts its color based on the background. The application intelligently switches between black and white text to ensure maximum visibility, regardless of whether you're working on a light or dark window.

## Features

- Real-time display of keyboard inputs
- Automatic text color adaptation based on background
- Clean, minimalist interface that stays out of your way
- Supports all common keyboard keys and combinations
- Convenient positioning at the bottom of your screen
- Low system resource usage

## Description

Perfect for presentations, screen recordings, or live demonstrations, AdaptiveKeyViewer shows your audience exactly which keys you're pressing in real-time. The application's intelligent contrast detection ensures that your key presses remain visible regardless of what's displayed on screen, eliminating the need to manually switch between dark and light modes.

## Requirements

- Python 3.x
- Required packages: pynput, pillow, numpy

## Installation

1. Make sure you have Python installed on your system
2. Install the required packages:
   ```
   pip install pynput pillow numpy
   ```
3. Save the script as `keyviz.py`

## Running the Application

To run AdaptiveKeyViewer, simply execute the Python script:

```
python keyviz.py
```

Or with the specific Python path:

```
"C:\Users\muham\AppData\Local\Programs\Python\Python313\python.exe" keyviz.py
```

## Usage

- The application will appear at the bottom of your screen
- Press any keys to see them displayed
- The text color will automatically adjust based on background brightness
- Press Esc + F12 simultaneously to exit the application

## Troubleshooting

- If the application doesn't start, ensure all required packages are installed
- For permission errors on some systems, try running with administrator privileges
- If key detection isn't working, make sure no other applications are intercepting keyboard events

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to improve functionality.

## License

This project is released under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built with Python and Tkinter
- Uses pynput for keyboard monitoring
- Employs PIL/Pillow for screen analysis
