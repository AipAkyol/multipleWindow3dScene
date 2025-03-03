# Multiple Window 3D Scene using Three.js

## Introduction
This project demonstrates a unique approach to creating and managing a 3D scene across multiple browser windows using Three.js and localStorage. It's designed for developers interested in advanced web graphics and window management techniques.

## Features
- 3D scene creation and rendering with Three.js
- Synchronization of 3D scenes across multiple browser windows
- Dynamic window management and state synchronization using localStorage

## Running the Project
1. Start a local Python HTTP server:
   - For Python 3.x:
     ```
     python -m http.server 8000
     ```
   - For Python 2.x:
     ```
     python -m SimpleHTTPServer 8000
     ```
2. Open your browser and navigate to `http://localhost:8000`
3. Click anywhere to create new windows with synchronized 3D scenes

## Project Structure
- `index.html`: Entry point and HTML structure
- `WindowManager.js`: Manages window synchronization and state
- `main.js`: 3D scene initialization and rendering logic
- `three.r124.min.js`: Three.js library

## License
This project is open-sourced under the MIT License.

## Acknowledgments
- The Three.js team for their comprehensive 3D library
- This is a fork of the original project with modifications to implement spheres instead of the original geometric shapes.
- Original repository by [@_nonfigurativ_](https://twitter.com/_nonfigurativ_)
