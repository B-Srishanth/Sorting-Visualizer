# Sorting Visualizer

An interactive, JavaScript-based web application that visually demonstrates how popular sorting algorithms work.  
Users can customize the array size and animation speed to observe step-by-step sorting behavior in real time.

## Features

- Real-time visualization using animated bars
- User-controlled array size and sorting speed
- Step-by-step execution of sorting algorithms
- Simple and intuitive user interface

## Implemented Algorithms

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort

## Project Structure

├── index.html # Main HTML file
├── style.css # Styling for the visualizer
├── JavaScript_files/
│ ├── sorting.js # Array generation & utility functions
│ ├── bubble_sort.js # Bubble Sort implementation
│ ├── selection_sort.js # Selection Sort implementation
│ ├── insertion_sort.js # Insertion Sort implementation
│ ├── merge_sort.js # Merge Sort implementation
│ └── quick_sort.js # Quick Sort implementation

## How It Works

- A random array is generated and displayed as vertical bars.
- Each bar’s height represents the value of an array element.
- Sorting algorithms animate comparisons and swaps.
- Color changes highlight active elements and sorted sections.

## Usage

1. Open `index.html` in any modern web browser.
2. Click **Input** to generate a new random array.
3. Adjust:
   - **Size** slider to control the number of elements
   - **Speed** slider to control visualization speed
4. Select any sorting algorithm to start visualization.

## Technologies Used

- **HTML5** – structure
- **CSS3** – styling and animations
- **JavaScript (ES6)** – algorithm implementation

## Notes

- Built for educational purposes to understand sorting algorithms visually.
- Larger arrays with slower speeds provide clearer step-by-step insight.
- All sorting algorithms are implemented from scratch.

## Author

**B. Srishanth**  
B.Tech, Electronics and Communication Engineering  
Indian Institute of Technology Guwahati
