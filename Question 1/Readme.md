The lammps script employs an NVT ensemble (fix mynvt all nvt temp ${Ti}
${Tf} 0.1) to heat the gold cube from 1 K to 2500 K:

a) Considering that gold has a well-defined melting point (~1337 K), how would you determine the exact melting point from this
simulation? What atomic-scale signatures (e.g., structural changes, diffusion behaviour) would confirm the phase transition?

b) The simulation tracks the atomic positions and velocities using a
timestep of 0.001 ps. Share the snapshots of the model as phase
change occurs. Given the melting process, how would the choice of
timestep influence the accuracy of the results? Specifically, discuss
the effects of using a smaller or larger timestep on the dynamics of
phase transition and energy conservation.
