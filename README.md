# 🎄 Magical Christmas Tree

A Creative Technology experiment combining **WebGL (Three.js)** and **Computer Vision (MediaPipe)** to create an interactive holiday experience.

![Christmas Tree Preview](https://via.placeholder.com/800x400?text=Merry+Christmas+WebGL+Experience)

## ✨ Features

- **Procedural Particle System**: Over 4000 particles forming a dynamic Christmas tree.
- **Gesture Control**: Use your webcam to control the scene with hand gestures.
- **Photo Memories**: Upload your own photos to add them to the 3D scene instantly.
- **Cinematic Rendering**: Uses PBR materials, Bloom (Glow) effects, and Tone Mapping.
- **Responsive & Fallback**: Works on mobile and desktop, with mouse interaction fallback if no camera is detected.

## 🎮 How to Interact

| Mode | Gesture / Action | Description |
|------|------------------|-------------|
| **TREE** | ✊ **Fist** (or Click) | Particles assemble into a spiral Christmas tree. |
| **SCATTER** | 🖐 **Open Hand** (or Click) | Particles explode into a chaotic snow globe effect. |
| **FOCUS** | 👌 **Pinch** (Index+Thumb) | Selects a random photo memory and brings it to the front. |
| **ROTATE** | 👋 **Move Hand/Mouse** | Rotate the entire scene based on hand or mouse position. |

## 🚀 Quick Start (Locally)

1. Clone this repository.
2. Because this project uses ES Modules, you need a local server.
   - **VS Code**: Install "Live Server" extension -> Right click `index.html` -> "Open with Live Server".
   - **Python**: Run `python -m http.server` in the terminal.
3. Open `localhost:port` in your browser.
4. Allow Camera permissions for the full experience.

## 🛠 Tech Stack

- **Three.js (r160)**: 3D Rendering engine.
- **Google MediaPipe**: Hand tracking and gesture recognition.
- **Vanilla JS (ES6+)**: No bundlers needed (Import Maps used).

## 📄 License

MIT License. Feel free to use this for your holiday greetings!