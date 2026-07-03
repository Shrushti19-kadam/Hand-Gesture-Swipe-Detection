# Hand Gesture Swipe Detection

## Overview

Hand Gesture Swipe Detection is a computer vision project developed using **Python**, **OpenCV**, and **MediaPipe**. The system detects hand swipe gestures in real time through a webcam by tracking the movement of the index finger. Based on the detected gesture, it simulates keyboard arrow key presses using **PyAutoGUI**, enabling touchless interaction with applications.

---

## Features

* Real-time hand detection using MediaPipe
* Index finger tracking
* Swipe gesture detection
* Detects four swipe directions:

  * Left
  * Right
  * Up
  * Down
* Simulates keyboard arrow key presses
* Live webcam display with hand landmarks
* Gesture cooldown to avoid repeated key presses

---

## Technologies Used

* Python
* OpenCV
* MediaPipe
* PyAutoGUI
* NumPy

---

## Project Structure

```text
Hand-Gesture-Swipe-Detection/
│
├── handgame.py
├── requirements.txt
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Hand-Gesture-Swipe-Detection.git
```

### Move to the project folder

```bash
cd Hand-Gesture-Swipe-Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python main.py
```

---

## How It Works

1. Captures live video from the webcam.
2. Detects a hand using MediaPipe.
3. Tracks the tip of the index finger.
4. Compares consecutive finger positions.
5. Detects the swipe direction.
6. Simulates the corresponding keyboard arrow key using PyAutoGUI.

---

## Swipe Directions

| Gesture     | Keyboard Action |
| ----------- | --------------- |
| Left Swipe  | Left Arrow Key  |
| Right Swipe | Right Arrow Key |
| Up Swipe    | Up Arrow Key    |
| Down Swipe  | Down Arrow Key  |

---

## Applications

* Touchless presentation control
* Image and document navigation
* Human-Computer Interaction (HCI)
* Gesture-based interfaces
* Computer vision learning projects

---

## Future Enhancements

* Support for multiple hand gestures
* Custom keyboard shortcuts
* Gesture sensitivity adjustment
* Volume and media control
* Mouse cursor control

---

## Author

**Shrushti Kadam**

B.Tech. Artificial Intelligence and Data Science

---

