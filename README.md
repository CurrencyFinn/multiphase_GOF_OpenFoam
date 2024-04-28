# multiphase_GOF_OpenFoam
Multiphase simulation of continuous gas phase and an oil Lagrangian particle using OpenFOAM's pimpleFoam solver and icoUncoupledKinematicParcelFoam solver.

## Task List

| Task                                  | Description                                     | Status      |
|---------------------------------------|-------------------------------------------------|-------------|
| Conversion PimpleFoam                                | Change IcoFoam to PimpleFoam including pseudo timestep, also steady state solver                          | Finished |
| Data Table                                | Tabluted constants such as viscosity, density etc.                          | Finished   |
| Reduce write contents icoUncoupledKinematicParcelFoam                                | The write contents only include the needed information for post-processing such as position velocity, and particle condition.                          | Not Started |
| Brownian motion                                | Investigate the implementation of Brownian motion and validate the effect                          | In progress |
| Restructure cases                                | Restructuring of all taken simulations in folder format + setup the case to the size dimension                         | Finished |
| Evaluate Fibres                                | Fibre mesh look into possible changes to geometry needed                        | In progress |
