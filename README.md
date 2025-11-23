# 📊 Sorting Visualizer

A web-based tool to visualize how various sorting algorithms work in real-time. Built with **HTML**, **CSS**, and **Vanilla JavaScript**.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 🚀 Live Demo
> [**Click here to view the live project**](YOUR_GITHUB_PAGES_LINK_HERE)

*(Tip: You can host this for free using GitHub Pages! Go to Settings -> Pages -> Source: Main)*

## 📸 Screenshots
![App Screenshot](path/to/your/screenshot.png)
*(Place a screenshot or a GIF of the sorting in action here)*

## ✨ Features
* **Dynamic Array Generation:** Randomly generates a new set of bars with different heights.
* **Algorithm Visualization:** See how algorithms compare and swap elements in real-time.
* **Speed Control:** Adjust the visualization speed (Fast/Slow) to better understand the steps.
* **Color Coding:**
    * 🟦 **Default:** Standard bars.
    * 🟨 **Yellow:** Elements being swapped (if necessary).
    * 🟥 **Red:** Elements being compared.
    * 🟩 **Green:** Elements in their sorted position.

## 🛠️ Tech Stack
* **HTML5:** Structure of the visualizer (containers, buttons, inputs).
* **CSS3:** Styling, Flexbox layout for bar alignment, and color transitions.
* **JavaScript (ES6+):**
    * **DOM Manipulation:** Generating and updating bar heights.
    * **Async/Await:** Used to create the "delay" effect for animations.
    * **Event Listeners:** Handling user clicks and slider inputs.

## 🧮 Implemented Algorithms
* [ ] Bubble Sort
* [ ] Selection Sort 
* [ ] Insertion Sort 
* [ ] Merge Sort 
* [ ] Quick Sort
* [ ] Heap sort
* [ ] Radix Sort
* [ ] Counting Sort
* [ ] Shell Sort
* [ ] Cocktail Sort
* [ ] Bucket Sort

      

## 🧠 How it Works
The core of the visualization relies on asynchronous JavaScript.
1.  **State Management:** The app generates an array of integers.
2.  **Rendering:** Each integer is mapped to a `div` element with a height proportional to its value.
3.  **Sorting Logic:** As the sorting algorithm runs, it pauses execution using `await` and a custom `sleep()` function.
4.  **Visual Updates:** During these pauses, the CSS classes of the bars are updated (e.g., changing color to indicate a swap), allowing the user to see the algorithm's internal process step-by-step.

## 🤝 Contributing
Contributions are welcome! If you'd like to add a new sorting algorithm:
1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

*Built with ❤️ by Ankit Kumar Das*
