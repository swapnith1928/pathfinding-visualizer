# Pathfinding Visualizer

This project is a **Pathfinding Visualizer** built with HTML, CSS, and JavaScript. It allows users to visualize different pathfinding algorithms on a grid-based map.

🔗 **Live Demo**: [View it on Netlify](https://684adf3f52593aa229ad6872--euphonious-empanada-8582c3.netlify.app/)

## Features

- **Interactive Grid**: Click to add walls or move the start/end nodes.
- **Algorithms Implemented**:
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Dijkstra's Algorithm
- **Visual Feedback**: Animates the traversal of the algorithms step-by-step.

## Folder Structure

```
project4/pathfinding-visualizer/
├── index.html                  # Main HTML file
├── script.js                   # Controls interaction and visualization
├── style.css                   # Styles for layout and animations
└── algorithms/
    ├── bfs.js                  # BFS implementation
    ├── dfs.js                  # DFS implementation
    └── dijkstra.js             # Dijkstra's algorithm
```

## Getting Started

### Prerequisites

A modern web browser (Chrome, Firefox, Edge, etc.)

### How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pathfinding-visualizer.git
   ```
2. Navigate into the project folder:
   ```bash
   cd pathfinding-visualizer
   ```
3. Open `index.html` in your browser to start the visualizer.

## Future Improvements

Here are a few ideas to enhance the project in the future:

- Add **A\* Search Algorithm** for more efficient pathfinding
- Mobile friendly UI improvements
- Modify **generaterandommaze** such that it always generates a maze that has a path from start to end

## Deployment

This project is deployed on **Netlify** and publicly accessible at the link above.

## License

This project is licensed under the MIT License.
