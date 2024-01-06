# LadyBirdNetworkData

This script performs an extraction of the nodes and edges data to perform a network analysis on the character interactions in the screenplay of 'Lady Bird'.
It identifies when two characters interact based on their co-presence in scenes and quantifies these interactions.
Additionally, it assigns a gender to each character based on predefined information.

Installation:

You need Python 3 and the following packages: PyMuPDF, re, itertools, collections, and csv. 
Install them using pip:
$ pip install PyMuPDF

Usage:

Execute the script in an environment where the necessary packages are installed.
Ensure that the screenplay PDF file is in the same directory as the script or provide the correct path to the file.
The output will be two CSV files: 'nodes_data.csv' and 'edges_data.csv'.

The 'nodes_data.csv' file will contain three columns: Id, Label, and Gender.
The 'edges_data.csv' file will contain three columns: Source, Target, and Weight, representing the interaction counts.
"""

Jupyter lab/notebook is recommended

