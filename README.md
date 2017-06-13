# MDread2Numpy
MDTrajRead by using MDanalysis code reads and saves the Molecular Dynamics Simulation trajectory output files into Numpy arrays.

Saves the trajectoy into a 3D array "traj"
    Input: a traj file name
    Output: array with [frames, atoms, coordinates] 
    
    By using "Universe" code of "MDAnalysis"
    N. Michaud-Agrawal, E. J. Denning, T. B. Woolf, and O. Beckstein. 
    MDAnalysis: A Toolkit for the Analysis of Molecular Dynamics Simulations.
    J. Comput. Chem. 32 (2011), 2319-2327, doi:10.1002/jcc.21787. PMCID:PMC3144279
