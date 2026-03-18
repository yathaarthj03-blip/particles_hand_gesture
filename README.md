# Gesture Controlled 3D Particles

An interactive browser-based visual project that uses **hand gestures** to control a **3D particle system** in real time.

Built with:
- **Three.js** for 3D rendering
- **MediaPipe Hands** for hand tracking
- **JavaScript, HTML, CSS** for the app structure and logic

## Features

- Real-time **webcam-based hand tracking**
- **10,000 particle** 3D visualization
- Gesture-based interaction:
  - **Open Palm** → expands particle structure
  - **Closed Fist** → implodes particle structure
  - **Pinch Gesture** → switches particle shapes
  - **Hand Position** → changes particle colors
- Multiple particle templates:
  - Sphere
  - Heart
  - Flower
  - Saturn
  - Fireworks

## How It Works

The project tracks the user’s hand through the webcam using **MediaPipe Hands**.

Based on detected landmarks:
- A **pinch** between thumb and index finger changes the particle template
- An **open hand** increases expansion
- A **closed hand** reduces the form inward
- Hand position affects the particle **RGB color mapping**

The particles smoothly animate toward target coordinates for each selected template, creating a morphing effect.

## Tech Stack

- **Three.js**
- **MediaPipe Hands**
- **Camera Utils**
- **Vanilla JavaScript**
- **HTML5 / CSS3**

## Project Structure

```bash
particles.html
