# Project Template

## Project Description

The Anelastic Wave Propagation software (awp-odc-os) simulates wave propagation in a 3D viscoelastic or elastic solid. Wave propagation use a variant of the staggered grid finite difference scheme to approximately solve the 3D elastodynamic equations for velocity and stress. The GPU version offers the absorbing boundary conditions (ABC) of Cerjan for dealing with artificial wave reflection at external boundaries.

awp-odc-os is implemented in C and CUDA. The Message Passing Interface supports parallel computation (MPI-2) and parallel I/O (MPI-IO).

## Objectives

We propose to run experimentation of our Gordon-bell award winning AWP-ODC software on Azure Accelerator. The version we will use is optimized by OSU DK Panda’s group, called CUDA-Aware AWP-ODC, recently we provided permission for Azure access. Our proposed project relies on commercial cloud solutions for maximum availability and flexibility of the executing hardware. At SDSC, we have the Expanse system, which features direct scheduler-integration with the public cloud, leveraging high-speed networks to ease data movement to/from the cloud. This project will show a case study in combining highly scalable software capabilities and ubiquity of Azure resource.

## Deliverables

* We will compare the performance of AWP-ODC on Azure and one native supercomputer (e.g.Expanse, Frontera). Based on our insights gained from this study, we will provide s set of guidelines how to scale the application on cloud and achieve the best performance.
* All software will be shared with the public under BSD-3. All processed and raw data (if feasible) will be CC0'd.
* Results and documentation will be published at highly visible venues.
* We will target full reproductivity through heavy time investments in respective artifact description and evaluation appendices.

## Contributors

- Yifeng Cui 
- Akash Palla
- Haochen Wang
- Hari Subramoni
- Qinghua Zhou
