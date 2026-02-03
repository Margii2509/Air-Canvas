# Air Canvas – Draw Using Hand Gestures

Air Canvas is a computer vision–based drawing application that lets you draw in the air using your hand gestures—no mouse, no pen, no touchscreen.  
It uses your webcam to track hand movements and converts them into digital drawings in real time.

---

# Features

- 🖐️ Hand gesture–based drawing
- 🎨 Multiple colors (Purple, Blue, Green, Yellow)
- 🧽 Eraser functionality
- 🖌️ Real-time drawing on a virtual canvas
- 🖥️ Live hand tracking using MediaPipe
- ⌨️ Keyboard controls to clear canvas and quit

---

# Technologies Used

- **Python**
- **OpenCV** – for webcam access and image processing
- **MediaPipe** – for hand detection and tracking
- **NumPy** – for canvas and array operations

---

# How It Works

- **Index Finger Up** → Draw on the canvas  
- **Index + Middle Finger Up** → Select color from the palette  
- **Black Color** → Acts as an eraser  
- The drawing is done by tracking the tip of the index finger

---

# Controls

| Action | Control |
|------|--------|
| Draw | Raise index finger |
| Select color | Raise index + middle finger |
| Clear canvas | Press `C` |
| Quit application | Press `Q` |

---

# Installation

1. Clone the repository:
   git clone https://github.com/Margii2509/Air-Canvas



# Run the Project
python air_canvas.py