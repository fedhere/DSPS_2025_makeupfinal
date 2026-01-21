# UDel DSPS Final 2025

## RULES:
Dont talk to anyone but Dr. Bianco about it, ask questions on slack by DM to Dr. Bianco. 

Name your notebook DSPS_Final_FLastname where F stands for your first initial and Lastname for your last name

Turn in by sharing with Dr. Bianco BEFORE 12PM (noon) on 1/24 -- best is to share it right away when you open the file, and continue to update it until the deadline

<img width="507" height="131" alt="Screenshot 2025-12-10 at 11 55 14 PM" src="https://github.com/user-attachments/assets/6abd9259-bfe7-402d-9803-806c2d1e74b4" />

<img width="507" height="521" alt="Screenshot 2025-12-10 at 11 54 57 PM" src="https://github.com/user-attachments/assets/a3fb3287-4afb-49c9-8e44-58be92e3eb42" />

Make sure you are making Dr. Bianco **Editor**

<img width="367" height="107" alt="Screenshot 2025-12-10 at 11 55 44 PM" src="https://github.com/user-attachments/assets/2a488a5a-fd76-4ad6-9aa9-45229d29bdac" />

## The assignent

You are to predict the coupling constant between two atoms given the two atom types (e.g., C and H), the coupling type (e.g., 2JHC), and any features you are able to create from the molecule structure (xyz) files.

you will use the data stored in train.csv

**train.csv** - the training set, where the first column (molecule_name) is the name of the molecule where the coupling constant originates (the corresponding XYZ file is located at ./structures/.xyz), the second (atom_index_0) and third column (atom_index_1) is the atom indices of the atom-pair creating the coupling and the fourth column (scalar_coupling_constant) is the scalar coupling constant that we want to be able to predict

**structures.csv** -- containing molecular structure (xyz) files, where the first line is the number of atoms in the molecule, followed by a blank line, and then a line for every atom, where the first column contains the atomic element (H for hydrogen, C for carbon etc.) and the remaining columns contain the X, Y and Z cartesian coordinates (a standard format for chemists and molecular visualization programs)
