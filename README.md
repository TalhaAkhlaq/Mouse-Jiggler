# Mouse Jiggler

This is a Mouse Jiggler script written in Python that automates mouse movement between two specified positions to prevent system inactivity. It allows for dynamic control of movement speed and toggling of the jiggle functionality through keyboard inputs.

## Features

- **Automated Mouse Movement**: Moves the mouse between two specified positions to simulate activity.
- **Adjustable Speed**: Change the movement speed using keyboard arrow keys.
- **Start/Pause Control**: Toggle the jiggle on or off using keyboard shortcuts.
- **Exit Control**: Quit the application using a keyboard shortcut.

## Getting Started

To use this Mouse Jiggler script, follow the steps below:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/mouse-jiggler.git
    cd mouse-jiggler
    ```

2. **Install the required libraries**:
    ```bash
    pip install pyautogui pynput
    ```

3. **Run the script**:
    ```bash
    python mouse_jiggler.py
    ```

## Usage

1. **Run the script**:
    ```bash
    python mouse_jiggler.py
    ```

2. **Setup Positions**:
   - Hover over the first position where you want the mouse to move and press Enter.
   - Hover over the second position and press Enter again.

3. **Keyboard Controls**:
   - Press `s` to start or pause the mouse jiggler.
   - Press the `up` arrow key to increase the movement speed.
   - Press the `down` arrow key to decrease the movement speed.
   - Press `q` to quit the script.

## Instructions

- **Main Functions**:
  - `move_mouse(pos1, pos2)`: Moves the mouse between two positions based on the global `active` flag.
  - `adjust_speed(key)`: Adjusts the movement speed based on arrow key input.
  - `on_press(key)`: Handles keyboard inputs for controlling the jiggle functionality and quitting the script.

- **Program Flow**:
  - The user is prompted to set up two mouse positions.
  - A separate thread continuously moves the mouse between the two positions.
  - A keyboard listener handles user inputs to control the jiggler and adjust the speed.

## Notes

- Administrative privileges are not required, but ensure your system allows for automated mouse movements.
- Use responsibly to avoid unintended interference with other applications.

## Disclaimer

Use this script responsibly. The author is not liable for any misuse or damage caused by running this software.

## Copyright & Licensing

Copyright (C) 2024 Talha Akhlaq <talhaakhlaq1@gmail.com>

Distributed under the MIT License. See `LICENSE` for details.
#
For more information on my projects and other academic work, please visit my [GitHub profile](https://github.com/TalhaAkhlaq).
