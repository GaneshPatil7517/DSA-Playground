# 🎯 DSA Playground

An interactive web application for visualizing Data Structures and Algorithms, built with React, Vite, and Tailwind CSS.

**🌐 Live Demo**: [https://ganeshpatil7517.github.io/DSA-Playground/](https://ganeshpatil7517.github.io/DSA-Playground/)

## ✨ Features

### 📊 Sorting Algorithms
- **5 Algorithms**: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort
- **Step-by-Step Mode**: Manual control with detailed explanations
- **Custom Array Input**: Enter your own values
- **Array Presets**: Random, Sorted, Reverse, Nearly Sorted
- **Speed Control**: Slow, Normal, Fast, Instant
- **Code Display**: View pseudocode for each algorithm
- **Complexity Cards**: Time and space complexity for all cases

### 🔗 Data Structures
- **Linked List**: Singly linked list with memory address visualization
- **Stack**: LIFO operations with use cases
- **Queue**: FIFO operations with animations
- **Binary Search Tree**: Insert, delete, search, and traversals (inorder, preorder, postorder)

### 🗺️ Pathfinding
- **Interactive Grid**: Draw walls by clicking and dragging
- **Algorithms**: BFS (Breadth-First Search), DFS (Depth-First Search)
- **Visualization**: Watch the algorithm explore the grid in real-time

### 🎨 UI/UX
- **Dark/Light Mode**: Toggle between themes
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Powered by Framer Motion
- **Professional Design**: Gradient cards, shadows, and modern UI

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/GaneshPatil7517/DSA-Playground.git
cd DSA-Playground
```

2. Install dependencies:
```bash
cd frontend
npm install
```

3. Run development server:
```bash
npm run dev
```

4. Open your browser and visit: `http://localhost:5173`

### Build for Production

```bash
npm run build
```

The production-ready files will be in the `frontend/dist` folder.

## 📁 Project Structure

```
DSA-Playground/
├── frontend/
│   ├── src/
│   │   ├── components/          # React components
│   │   │   ├── SortingVisualizer.jsx
│   │   │   ├── LinkedListVisualizer.jsx
│   │   │   ├── StackSimulator.jsx
│   │   │   ├── QueueSimulator.jsx
│   │   │   ├── BinaryTreeVisualizer.jsx
│   │   │   ├── PathfindingVisualizer.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── ComplexityCard.jsx
│   │   ├── algorithms/          # Algorithm implementations
│   │   │   └── sorting/
│   │   │       ├── bubbleSort.js
│   │   │       ├── selectionSort.js
│   │   │       ├── insertionSort.js
│   │   │       ├── mergeSort.js
│   │   │       └── quickSort.js
│   │   ├── pages/               # Page components
│   │   │   ├── Home.jsx
│   │   │   └── About.jsx
│   │   ├── App.jsx              # Main app component
│   │   ├── main.jsx             # Entry point
│   │   └── index.css            # Global styles
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.cjs
├── .github/
│   └── workflows/
│       └── deploy.yml           # GitHub Actions deployment
├── DEPLOYMENT.md                # Deployment guide
└── README.md
```

## 🛠️ Technologies Used

- **React 18.2.0** - UI library
- **Vite 5.2.0** - Build tool and dev server
- **Tailwind CSS 3.4.7** - Utility-first CSS framework
- **Framer Motion 10.12.16** - Animation library
- **React Router DOM 6.20.1** - Client-side routing
- **Lucide React 0.276.0** - Icon library

## 📚 Algorithms Implemented

### Sorting
1. **Bubble Sort** - O(n²) - Simple comparison-based sorting
2. **Selection Sort** - O(n²) - Selects minimum element repeatedly
3. **Insertion Sort** - O(n²) - Builds sorted array one element at a time
4. **Merge Sort** - O(n log n) - Divide and conquer approach
5. **Quick Sort** - O(n log n) avg - Partition-based sorting

### Pathfinding
1. **BFS** - Breadth-First Search - Explores level by level
2. **DFS** - Depth-First Search - Explores as deep as possible

### Tree Operations
1. **BST Insert** - Add nodes maintaining BST property
2. **BST Delete** - Remove nodes (handles 3 cases)
3. **BST Search** - Find nodes with path highlighting
4. **Traversals** - Inorder, Preorder, Postorder

## 🌐 Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions.

**Live URL**: https://ganeshpatil7517.github.io/DSA-Playground/

For detailed deployment instructions, see [DEPLOYMENT.md](./DEPLOYMENT.md)

## 👨‍💻 Developer

**Ganesh Patil**  
Google Developer Relations (DevRel)

- GitHub: [@GaneshPatil7517](https://github.com/GaneshPatil7517)
- LinkedIn: [Ganesh Patil](https://www.linkedin.com/in/ganesh-patil-9b74bb30b/)

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## ⭐ Show Your Support

Give a ⭐️ if this project helped you learn DSA concepts!

## 📸 Screenshots

### Sorting Visualizer
- Custom array input with presets
- Step-by-step mode with explanations
- Code display panel
- Speed controls

### Data Structures
- Linked List with memory addresses
- Stack with LIFO visualization
- Queue with FIFO operations
- Binary Tree with SVG rendering

### Pathfinding
- Interactive grid with wall drawing
- BFS/DFS visualization
- Path highlighting

---

**Made with ❤️ for DSA learners**
