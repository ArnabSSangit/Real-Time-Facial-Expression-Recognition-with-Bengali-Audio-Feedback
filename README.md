Real-Time Facial Expression Recognition with Bengali Audio Feedback
This repository contains the research and implementation of a deep learning system for real-time facial expression recognition, complete with an interactive web-based report. The project, titled "Real-Time Facial Expression Recognition with Bengali Audio Feedback: Bridging Communication Gaps," was developed as a B.Sc. thesis at Brac University.

🚀 Live Interactive Report
This project includes a fully interactive, single-page web application to visualize the research findings, compare model performance, and explore the dataset.



🌟 Features of the Interactive Report
Interactive Architecture Diagram: A step-by-step flowchart explaining the dual-stream deep learning model.

Dataset Exploration: A visual breakdown of the emotion distribution in the dataset, along with sample images.

Comparative Model Analysis: Dynamically switch between the custom model (Best_FER), ResNet-50, and MobileNetV2 to compare their learning curves and performance metrics.

In-Depth Results: An interactive confusion matrix and class-wise performance charts (Precision, Recall, F1-Score) for a deeper understanding of the final model's accuracy.

Author Information: Details about the researchers and their academic supervision.

Fully Responsive: The report is designed to be accessible on desktops, tablets, and mobile devices.

🗂️ Repository Contents
This repository is organized into the core components of the research project:

File

Description

index.html

The source code for the single-page interactive web report. You can open this file in a browser or host it on GitHub Pages.

best model with combined.ipynb

A Jupyter Notebook containing the implementation of the final, optimized CNN-RNN hybrid model (Best_FER).

best model.ipynb

An earlier or alternative version of the primary model notebook.

Feedback.ipynb

A Jupyter Notebook detailing the implementation of the LSTM model for generating Bengali feedback sequences.

dataset.txt

Contains metadata or paths related to the dataset used for training and validation.

🧑‍💻 Authors & Acknowledgements
This research was conducted by the following students at Brac University:



Arnab Sarker Sangit (19201100)

Sharthak Das (23241033)

The project was supervised by Mr. Moin Mostakim, Senior Lecturer in the Department of Computer Science and Engineering.

⚙️ How to Use
Viewing the Interactive Report
Online (Recommended): Click the Live Demo link at the top of this README.

Locally:

Clone or download this repository.

Navigate to the repository folder on your computer.

Open the index.html file directly in your web browser (e.g., Chrome, Firefox).

Running the Notebooks
To explore the model implementations:

Ensure you have a Python environment with Jupyter Notebook, TensorFlow/Keras, and other required libraries (pandas, numpy, matplotlib) installed.

Clone this repository.

Launch Jupyter Notebook from your terminal.

Navigate to the repository folder and open any of the .ipynb files to view and run the code cells.
