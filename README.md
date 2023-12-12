# Disk Scheduling Algorithm GUI

This Python program implements a graphical user interface (GUI) for visualizing and comparing different disk scheduling algorithms. The program uses the Tkinter library for the GUI, Turtle graphics for visualization, and Matplotlib for creating a bar graph to compare the total head movement of various algorithms.

## Prerequisites

- Python 3.x
- Tkinter
- Turtle
- Pandas
- Matplotlib
- Numpy

## Running the Program

1. Make sure you have Python installed on your system.

2. Install the required libraries using the following command:

   ```bash
   pip install pandas matplotlib numpy
   ```

3. Save the provided code in a Python file, e.g., `disk_scheduling_gui.py`.

4. Run the program using the following command:

   ```bash
   python disk_scheduling_gui.py
   ```

## Using the GUI

- Choose an algorithm from the dropdown menu.
- Enter the sequence of disk requests in the text box separated by spaces.
- Enter the starting position of the disk read/write head.
- Click the "Visualize" button to see the animation of the selected algorithm's disk scheduling.
- Click the "Graph" button to display a bar graph comparing the total head movement of different algorithms.

## Note

- The program uses Turtle graphics for visualization, and a new window will appear with the visualization.
- The Matplotlib graph will be displayed in a separate window.
- Close the visualization and graph windows to exit the program.

Feel free to explore and modify the code according to your needs!
