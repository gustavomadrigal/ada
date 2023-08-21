# ada
Summer Internship 2023: Adamantanone 

This Python script is for get the correct Adamantanone .PDB file. The script is a Jupyter Notebook file; the instructions within this README.md is for each Jupyter Notebook cell. Before using the script, you must get the Adamantanone .CIF file. 

Cell #1: 

1. You need to generate the Adamantanone .PDB file using the .CIF File. For this, you can use Mercury. For downloading Mercury: https://www.ccdc.cam.ac.uk/solutions/software/free-mercury/

2. This cell removes randomly the extra 2 Oxygen atoms and the extra 2 Hydrogen atoms associated with the Oxygen atom that is left. 

Cell #2:

1. This cell groups the moleculas every 25 atoms because the Adamantone has 25 atoms in its structure.

Cell #3:

1. This cell sorts the atoms, within every group, in the position that I defined. For example, the Oxygen atom is in the second row every 25 atoms.

Cell #4: 

1. This cells writes the the first and the last rows (HEADER and MASTER/END rows).

Cell #5: 

1. This cells gives the final and the correct .PDB file.
