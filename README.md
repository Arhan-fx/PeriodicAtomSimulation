# Periodic Atom Simulator

## Overview
The **Periodic Atom Simulator** is a Python-based application that uses the Pygame library to visualize atomic structures of periodic table elements. This simulation displays the nucleus, electron orbits, and dynamic electron movement for selected elements.

## Features
- **Atomic Visualization:** Displays the nucleus, electron shells, and electrons.
- **Interactive Element Navigation:** Switch between elements to observe their atomic structures.
- **Electron Animation:** Electrons revolve around the nucleus dynamically.
- **Adjustable Speed:** Modify the animation speed using arrow keys or the slider.

## Dependencies
- Python 3.x
- Pygame library

Install Pygame using the following command:
```bash
pip install pygame
```

## How to Run
1. Clone the repository or download the script file.
2. Ensure Python and Pygame are installed on your system.
3. Run the script using the following command:
   ```bash
   python <script_name>.py
   ```

## Controls
- **Navigate Elements:**
  - Use the **Up (\u25B2)** and **Down (\u25BC)** buttons on the screen to switch between elements.
- **Adjust Speed:**
  - Use **Left Arrow** to decrease speed.
  - Use **Right Arrow** to increase speed.
  - Alternatively, use the slider to set speed.

## Supported Elements
The simulator currently supports the following elements:
- Hydrogen (H)
- Helium (He)
- Lithium (Li)
- Beryllium (Be)
- Boron (B)

## Application Components
1. **Atomic Data:** Stores the properties of each supported element (symbol, atomic number, mass number, etc.).
2. **Draw Atom Function:** Visualizes the nucleus, shells, and electrons dynamically.
3. **Speed Control:** Adjusts the electron animation speed interactively.
4. **GUI Buttons and Slider:** Provides an intuitive interface for navigation and control.

## Customization
To add more elements, update the `atomic_data` dictionary with the new element's properties, including the symbol, atomic number, mass number, number of neutrons, and electron configuration.

## Screenshots
Add screenshots or gifs to showcase the simulator in action.

---

### Disclaimer
This project is for educational purposes and demonstrates basic atomic visualizations. It does not account for complex quantum mechanics or real-world electron behavior.

