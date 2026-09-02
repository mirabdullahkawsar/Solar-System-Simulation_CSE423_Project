# Solar System Simulation
# Computer Graphics_CSE423

A **2D Solar System Simulation** developed using **Python and PyOpenGL**. The project demonstrates computer graphics concepts such as circle drawing, animation, transformations, random particle generation, and interactive controls.

## ✨ Features

* ☀️ Animated Sun with:
  * Pulsing effect
  * Corona and halo
  * Sunspots
* 🪐 Six rotating planets with different sizes, colors, and orbital distances
* 🌌 Large star field with twinkling stars
* ☄️ Moving comet with a tail
* 🪨 Asteroid belt
* 🌠 Meteor shower
* 🌌 Nebula and spiral galaxy
* 🕳️ Black hole with event horizon
* 💥 Animated supernova
* ⭐ Moving star cluster
* 🌟 Pulsar animation
* 🛰️ Space station
* 🔍 Zoom control
* ⏸️ Pause/Resume animation
* ⚡ Adjustable simulation speed

## 🛠️ Technologies

* **Python**
* **PyOpenGL**
* **OpenGL**
* **GLUT**
* **GLU**
* `math`
* `random`
* `time`

## 🎮 Controls

| Control            | Action         |
| ------------------ | -------------- |
| `Space`             | Pause / Resume |
| Left Mouse Button   | Decrease speed |
| Right Mouse Button  | Increase speed |
| Mouse Wheel Up      | Zoom In        |
| Mouse Wheel Down    | Zoom Out       |

## ⚙️ How It Works

The program creates an OpenGL window and continuously redraws the scene through the GLUT animation loop.

The main rendering process is handled by:

```text
display()
   │
   ├── Solar orbit paths
   ├── Sun
   ├── Stars
   ├── Planets
   ├── Asteroid belt
   ├── Comet
   ├── Nebula
   ├── Galaxy
   ├── Black hole
   ├── Pulsar
   ├── Supernova
   └── Space station
```

The `animate()` function continuously updates the positions, rotations, pulsing effects, and supernova radius.

### Graphics Algorithms

The project also implements circle drawing using the **Midpoint Circle Algorithm**:

```python
midCircle()
```

while filled circular objects are generated using polygon-based circle approximation:

```python
midCirc()
```

Randomized particle generation is used for stars, nebulae, meteors, space dust, galaxies, and other space effects.

## 📂 Project Structure

```text
Solar-System-Simulation/
│
├── main.py
└── README.md
```

## 🚀 Run the Project

Install the required library:

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

Then run:

```bash
python main.py
```

## 🎓 Project Focus

This project demonstrates fundamental **Computer Graphics** concepts including:

* OpenGL rendering
* 2D geometric primitives
* Circle drawing algorithms
* Animation and transformations
* Coordinate systems
* Random particle systems
* User interaction
* Double buffering
* Perspective projection

## 👨‍💻 Project

**Solar System Simulation**
**Language:** Python
**Graphics Library:** PyOpenGL
**Platform:** OpenGL / GLUT
