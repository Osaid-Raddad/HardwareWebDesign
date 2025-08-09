# Igris Robot Control Panel (Frontend Design)

This is the **frontend UI design** for the Igris robot — a Raspberry Pi-powered guide robot that helps new students navigate to their halls.  
This version contains **only the design** (no backend functionality yet) and is meant to be displayed on a touch screen connected to the Raspberry Pi.

## Features

### 1. Modern Navbar
- Displays the robot name: **Igris Robot**.
- Includes a **Dark/Light mode toggle** button.
- **Two navigation tabs**:
  - **Auto Mode**
  - **Remote Control Mode**
- Selected tab remains highlighted in both light and dark mode.

### 2. Auto Mode
- One large button to activate the robot in **automatic navigation mode**.

### 3. Remote Control Mode
- Buttons for:
  - Activating stepper motors.
  - Activating servo motor for bottle recycling.
  - Activating servo motor for camera direction.
- **Speed Control Buttons**:
  - Speed Level 1
  - Speed Level 2
  - Speed Level 3
- **Action Log Box**:
  - Displays feedback messages when buttons are pressed.

### 4. Ultrasonic Sensor Readings
- Four placeholders for live distance readings:
  - Front Right
  - Front Left
  - Back Right
  - Back Left

### 5. Modern Styling
- Built with **Tailwind CSS** for a responsive and clean design.
- All buttons share the same primary color with hover effects.
- Smooth Dark/Light mode transitions.

---

## Technologies Used
- **HTML5**
- **Tailwind CSS** (via CDN)
- **JavaScript** for:
  - Tab switching
  - Dark/Light mode toggle
  - Logging button actions

---

## Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/Osaid-Raddad/HardwareWebDesign.git
cd HardwareWebDesign
