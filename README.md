# GuideRNA-UCSC-Visualization
GuideRNA-UCSC-Visualization
This repository contains a Python-based workflow to generate UCSC Genome Browser links with custom tracks for visualizing guide RNA sequences. The guide RNA sequences are produced using CASowary, targeting long non-coding RNAs (lncRNAs), and are visualized using the UCSC Genome Browser.

Project Overview

This project consists of two main components:

Guide RNA Generation: The guide RNA sequences used in this project were generated using CASowary, which can be found at the official repository: CASowary GitHub. CASowary was used to produce guide sequences specifically targeting long non-coding RNAs (lncRNAs).

UCSC Genome Browser Link Generation: Once the guide RNA sequences were generated, this project includes a Python script that creates UCSC Genome Browser links with custom tracks for visualizing the guide RNAs.

Installation git clone https://github.iu.edu/sbabburi/GuideRNA-UCSC-Visualization cd GuideRNA-UCSC-Visualization

Open the Jupyter Notebook: Launch Jupyter Notebook and open the .ipynb file in your local environment: jupyter notebook UCSC_LINK Code.ipynb

Run the Cells: Follow the instructions in the notebook and run the code cells to generate the UCSC Genome Browser links.

Example Output

The notebook generates a CSV file containing UCSC Genome Browser links, allowing you to visualize the guide RNA sequences. The output file includes the following columns:
   Transcript_Name: The transcript associated with the RNA.
	 Guide_Sequence: The sequence of the guide RNA.
   Gene_Name: The name of the target gene.
	 Chromosome: The chromosome where the gene is located.
	 Start: The starting position of the guide RNA.
	 End: The ending position of the guide RNA.
	 Strand: The strand orientation.
	 UCSC_URL: The link to visualize the guide RNA in UCSC Genome Browser.

Notes
Ensure that the input file containing guide RNA sequences and gene information is formatted correctly before running the notebook.
This project uses manually specified coordinates for long non-coding RNAs to ensure accurate visualization.

License

This project is licensed under the MIT License.
