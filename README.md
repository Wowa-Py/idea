# idea
Statistics: the work of the model with deviations of the floor angles from the ceiling angles.

This is a Python project that visualizes data from a JSON file. It consists of several files and functions:

- plotter.py - a class Plotter that handles the visualization of data from a JSON file. It contains a method 
draw_plots that creates histograms for each column in the DataFrame, saves them in the folder_path folder, and returns the paths to the saved plots.

- draw_plots.py - a function draw_plots that creates an instance of the Plotter class and calls its draw_plots method. 
It takes a JSON file path as a parameter and a folder path for saving the plots as a parameter. It returns a list of paths to the saved plots.

- deviation.json - a JSON file containing data for visualization.

- charts - a folder for saving the plots.

- Notebook.ipynb - a Jupyter notebook that calls the draw_plots function and displays the saved plots.
