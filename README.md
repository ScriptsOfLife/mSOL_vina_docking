## Docking with Autodock Vina for Computer Aided Drug Discovery (CADD)

In this tutorial, you will learn to perform Molecular docking with Autodock Vina using python script.
You need to perform few steps before using this python script for docking.

prerequisite
Step 1. Retrieve PDB structure of your protein target from Protein Data Bank (PDB).
Step 2. Prepare your protein usning UCSF Chimera and Autodock4.
	a. Analyze the PDB structure and remove heteroatoms that are not important.
	   (Keep those heteroatoms that are important for docking for your protein of interest)
	b. Add Hydrogens
	c. Add charges
	d. Save prepare protein as receptor.pdbqt
Step 3. Identify binding site where you want to perform docking.
Step 4. Generate receptor grid for docking.
Step 5. Save the coordinates of receptor grid in conf.txt file. (as an example, you can have a look at the provided conf.txt file)
Step 6. Place your ligand to be used for docking inside input_docking folder.

Now, make an virtual environment using conda for installing `openbabel`

	conda create -n babel-env python=3.9
	conda activate babel-env

### install openbabel

	pip install openbabel
	conda install -c conda-forge notebook
	conda install -c conda-forge pandas
	conda install -c conda-forge numpy

Now open jupyter notebook

	`jupyter notebook`
	
You are ready to use python script for forming docking using Autodock Vina

Run the script. That's it !!

Good luck! I hope you find these materials helpful.

I am working on more tutorial and upload them soon.

Till then keep exploirng keep learning.
