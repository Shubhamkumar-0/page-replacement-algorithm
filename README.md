# page-replacement-algorithm
Page Replacement Algorithms Simulator
Overview
This project provides a comprehensive overview and interactive simulation of various page replacement algorithms used in operating systems. Page replacement algorithms are crucial for managing the contents of a system's memory and ensuring optimal performance. This simulator lets users understand how algorithms like FIFO, LRU, and Optimal work, and allows them to visualize how page replacements occur in real-time, with a user-defined reference string and number of frames.<br><br>

The project includes detailed explanations of each algorithm, accompanied by their strengths and weaknesses, followed by a hands-on simulator where users can experiment with their own data to observe how the algorithms perform.<br><br>

Features
📘 Informative Content
FIFO (First-In, First-Out): Understand the basic concept of FIFO, where the oldest page is replaced first. Learn about its simplicity and drawbacks, such as Belady’s Anomaly, where increasing the number of frames can actually result in more page faults.<br><br>

LRU (Least Recently Used): Learn how LRU optimizes page replacement by replacing the least recently used page. Explore its performance improvements over FIFO and its requirement for additional memory structures, such as a stack or map.<br><br>

Optimal Algorithm: Understand the theoretical "best" algorithm, which minimizes page faults by replacing the page that will not be used for the longest time in the future. While optimal in terms of performance, it's not practical for real-time systems.<br><br>

Each algorithm includes:

Pros: Key advantages of using the algorithm.

Cons: Limitations and potential pitfalls of the algorithm.

Use Cases: Where each algorithm shines and where it may fall short.<br><br>

🧠 Interactive Simulator
User Input: You can provide your own reference string (sequence of memory accesses) and frame count (number of pages that can be held in memory).<br><br>

Real-time Simulation: The simulator visualizes each step of the page replacement process, showing which page is loaded, which is replaced, and how the algorithm performs.<br><br>

Live Metrics: Get a real-time update on the number of page faults and hits to understand the efficiency of the algorithm for your input.<br><br>

📊 Comparison Table
A comparison table summarizes the efficiency, pros, and cons of FIFO, LRU, and Optimal. It visually compares:

Page Faults: How many page faults occurred during the simulation.

Execution Time: Time taken to process the given input.

Efficiency: A relative efficiency comparison based on the number of page faults.

Memory Overhead: How much additional memory is required by each algorithm to track page usage (particularly relevant for LRU).<br><br>

🌍 Responsive Design
Device Compatibility: The simulator is designed to work seamlessly on desktops, tablets, and smartphones. It adjusts the layout and user interface to provide an optimal experience on any screen size.<br><br>

💻 Demo and Visuals
Interactive animations visually demonstrate the replacement of pages and the effect of each algorithm. See how the frames change dynamically as pages are added or replaced, providing an intuitive understanding of how these algorithms function.<br><br>

Technologies Used
HTML: Used for the structure and layout of the web page.<br>

Tailwind CSS: A utility-first CSS framework that helps to quickly create a responsive and attractive user interface.<br>

JavaScript: Implements the logic behind the page replacement algorithms and provides real-time simulation and interactivity.<br>

Local Storage (optional): For saving user settings and reference strings for repeated use.<br><br>


