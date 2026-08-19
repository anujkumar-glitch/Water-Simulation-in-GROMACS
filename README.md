# Water-Simulation-in-GROMACS

gmx_mpi solvate -cs spc216.gro -box 5 5 5 -o water_box.gro

gmx_mpi pdb2gmx -f water_box.gro -o new_water_box.gro -p topol.top

Select CHARMM all-atom force field by pressing 1 and then enter. 

Select the TIP3P Water Model by pressing 1 and then enter.  
 
