# EpidemicSimulation
A simple Python program to model the spread of a virus in a population. Makes use of Python's tkinter module to create a GUI for user interaction.

# USAGE
To use the program, simply double click the Simulation.pyw file. This should open up the simulation window.

From here, pressing 'Unpause' will begin the simulation. You can change any of the parameters on the left, 
but they will not be applied until the 'Reset' button is pressed.

Pressing the 'Save' button will save the history of the susceptible, infected and recovered population values
for this current trial, as well as the corresponding tick values and the epidemiological values over time.
The data will be saved into a file named data.txt in the same directory as the Simulation.pyw file. Ensure
that this file is closed before overriding, in order to avoid concurrent modification issues. The data will be
saved in a format that is ready to be copy and pasted directly into MATLAB, as arrays that can be plotted.

The program can be closed at any time with the 'Quit' button, or by simply closing the window.

# REQUIREMENTS
The program was written in Python 6, 64-bit, but should generally work on most versions.

The GUI is programmed using tkinter, which is included in the Python standard library and so should work without
needing manual install.

I ran this simulation on a Ryzen 5 3600 with 16GB of 3600MHz RAM. I did not see any performance issues until
the population was increased to above 500.


If you encounter any issues let me know!
