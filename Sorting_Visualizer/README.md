# Sorting_Visualizer

A web application showcasing the inner workings of sorting algorithms.

Implemented algorithms:
1) Bubble sort
2) Selection sort
3) Insertion sort
4) Merge sort
5) Quick sort
6) Heap sort

Features:
1) Colored representation of step being executed.
  1.1) Blue:default
  1.2) Yellow: Being compared
  1.3) Red: Identified as in incorrect position and to be moved
  1.4) Green: In correct position
2) 3 Controls for visualizations
  2.1) Speed of visualization (5 speed levels)
  2.2) Data size ()
  2.3) Generation of new data (Randomly generate new data).
4) Time and Space complexity of algorithm being visualized.

# Sorting Algorithm Visualizer

## Overview
Sorting Algorithm Visualizer is an interactive web-based tool designed to help users understand how various sorting algorithms work. This project visually demonstrates the step-by-step process of sorting through algorithms like Quick Sort, Merge Sort, and Bubble Sort. By observing these algorithms in real-time, users can grasp key concepts such as comparisons, swaps, and recursion.

The tool is built using **React** for dynamic rendering, with **JavaScript** implementations of sorting algorithms. It’s ideal for both students learning data structures and algorithms (DSA) and anyone interested in exploring the efficiency of sorting techniques.

## Features
- **Algorithms Supported:**
  - Quick Sort
  - Merge Sort
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
- Real-time visualization of sorting process
- Adjustable array size and sorting speed
- Simple and intuitive user interface
- Color-coded visual representation of comparisons and swaps
- Responsive design for desktop and mobile

## Tech Stack
- **Frontend:** React, HTML5, CSS3, JavaScript (ES6+)
- **Backend:** N/A (fully client-side)
- **Libraries Used:** React.js

## How It Works
- The user selects the sorting algorithm from the list of available options.
- The user can set the array size and control the speed of sorting.
- The algorithm runs and displays each step of sorting visually, with elements being compared and swapped highlighted in real-time.
- Once completed, the sorted array is shown.

## Installation and Setup

### Prerequisites
- Node.js installed on your machine
- npm (Node package manager)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/Kumman123/sorting-visualizer.git
   
2.Navigate into the project directory:
   cd sorting-visualizer

3.Install the necessary dependencies:
    npm install

4.Start the development server:
    npm start

5.Open the application in your browser at http://localhost:3000.

