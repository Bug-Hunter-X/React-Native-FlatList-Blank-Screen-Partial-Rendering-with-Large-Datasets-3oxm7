# React Native FlatList Rendering Issue

This repository demonstrates a common issue encountered when using FlatList in React Native with large datasets: blank or partially rendered screens. The issue stems from memory limitations and inefficient rendering of many list items.

## Bug Reproduction

The `bug.js` file contains code that attempts to render a large array using FlatList, leading to incomplete rendering. To reproduce, simply run the app.  You should see either a blank screen or only a portion of the list displayed.

## Solution

The `bugSolution.js` file provides a solution using techniques like `windowSize` and `getItemLayout` within FlatList to optimize rendering and memory management.   This should resolve the blank screen/partial rendering problem.

## Technologies Used

* React Native