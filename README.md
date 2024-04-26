# multiphase_GOF_OpenFoam
Multiphase simulation of continuous gas phase and an oil Lagrangian particle using OpenFOAM's pimpleFoam solver and icoUncoupledKinematicParcelFoam solver.

## Task List

| Task                                  | Description                                     | Status      |
|---------------------------------------|-------------------------------------------------|-------------|
| Conversion PimpleFoam                                | Change IcoFoam to PimpleFoam including pseudo timestep                          | In Progress |
| Data Table                                | Tabluted constants such as viscosity, density etc.                          | Not Started   |
| Reduce write contents icoUncoupledKinematicParcelFoam                                | The write contents only include the needed information for post-processing such as position velocity, and particle condition.                          | Not Started |
| Brownian motion                                | Investigate the implementation of Brownian motion and validate the effect                          | Not Started |
