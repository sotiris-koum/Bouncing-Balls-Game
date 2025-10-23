# Ball Physics Simulation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pygame](https://img.shields.io/badge/Pygame-2.5.1-green)
![NumPy](https://img.shields.io/badge/NumPy-1.24.3-orange)

## ✨ Features
- **Realistic Physics**: Elastic collisions, gravity, and momentum conservation
- **Dynamic Escape Mechanism**: Rotating arc that allows balls to escape
- **Particle System**: Automatic ball generation and destruction
- **Mathematical Accuracy**: Uses NumPy for precise vector calculations
- **Visual Appeal**: Colorful balls with random colors

## 📋 Requirements
- Python 3.8+
- Pygame 2.5.1
- NumPy 1.24.3

## 🎮 How It Works
- Balls start inside the circle with random velocities
- They bounce elastically off the circle's boundaries
- Gravity pulls them downward
- A rotating arc periodically allows balls to escape
- When a ball escapes, two new balls are generated

## 🔬 Technical Details
- **Physics Engine**: Custom implementation using vector mathematics
- **Collision Detection**: Precise circle-boundary collision algorithms
- **Coordinate System**: Cartesian with NumPy array optimization
- **Rendering**: Pygame for real-time visualization

## ⚠️ Known Issues
- The simulation may crash after extended runtime due to exponential ball growth
- This is intentional for demonstration purposes

## 🤝 Contributing
Contributions welcome! Feel free to fork and submit pull requests.
