Supporting data for the paper:

# Decoding Cancer-Associated Mutations in DNA Polymerase η through atomistic simulations.

[![DOI](https://img.shields.io/badge/DOI-10.1021%2Fjtct.6c00345-darkgreen)](https://doi.org/10.1021/acs.jctc.6c00345.)

This repository contains the input files and simulation protocols used for molecular dynamics (MD) simulations of Xeroderma Pigmentosum Variant (XP-V)-associated mutations in human DNA polymerase η (Polη) in complex with DNA.

The studied XP-V-associated variants are:
- Arg93Pro
- Arg111His
- Ala117Pro
- Thr122Pro
- Gly263Val
- Val266Asp
- Gly295Arg
- Arg361Ser

Simulations were performed for both the pre-translocation (III) and post-translocation (IV) states of the catalytic cycle.

---


# Topology Files for AMBER (`.prmtop`)
These files contain the topology and force-field parameters for each simulated system, generated with tleap (AmberTools25). 

## Arg93Pro (R93P)
- `R93P_pre_all.prmtop` – Pre-translocation state topology
- `R93P_post_all.prmtop` – Post-translocation state topology

## Arg111His (R111H)
- `R111H_pre_all.prmtop` – Pre-translocation state topology
- `R111H_post_all.prmtop` – Post-translocation state topology

## Ala117Pro (A117P)
- `A117P_pre_all.prmtop` – Pre-translocation state topology
- `A117P_post_all.prmtop` – Post-translocation state topology

## Thr122Pro (T122P)
- `T122P_pre_all.prmtop` – Pre-translocation state topology
- `T122P_post_all.prmtop` – Post-translocation state topology

## Gly263Val (G263V)
- `G263V_pre_all.prmtop` – Pre-translocation state topology
- `G263V_post_all.prmtop` – Post-translocation state topology

## Val266Asp (V266D)
- `V266D_pre_all.prmtop` – Pre-translocation state topology
- `V266D_post_all.prmtop` – Post-translocation state topology

## Gly295Arg (G295R)
- `G295R_pre_all.prmtop` – Pre-translocation state topology
- `G295R_post_all.prmtop` – Post-translocation state topology

## Arg361Ser (R361S)
- `R361S_pre_all.prmtop` – Pre-translocation state topology
- `R361S_post_all.prmtop` – Post-translocation state topology

---

# Coordinate / Restart Files for AMBER (`.rst7`)
These files contain the initial atomic coordinates used to start the simulations.

## Arg93Pro (R93P)
- `R93P_pre_all.rst7` – Pre-translocation coordinates
- `R93P_post_all.rst7` – Post-translocation coordinates

## Arg111His (R111H)
- `R111H_pre_all.rst7` – Pre-translocation coordinates
- `R111H_post_all.rst7` – Post-translocation coordinates

## Ala117Pro (A117P)
- `A117P_pre_all.rst7` – Pre-translocation coordinates
- `A117P_post_all.rst7` – Post-translocation coordinates

## Thr122Pro (T122P)
- `T122P_pre_all.rst7` – Pre-translocation coordinates
- `T122P_post_all.rst7` – Post-translocation coordinates

## Gly263Val (G263V)
- `G263V_pre_all.rst7` – Pre-translocation coordinates
- `G263V_post_all.rst7` – Post-translocation coordinates

## Val266Asp (V266D)
- `V266D_pre_all.rst7` – Pre-translocation coordinates
- `V266D_post_all.rst7` – Post-translocation coordinates

## Gly295Arg (G295R)
- `G295R_pre_all.rst7` – Pre-translocation coordinates
- `G295R_post_all.rst7` – Post-translocation coordinates

## Arg361Ser (R361S)
- `R361S_pre_all.rst7` – Pre-translocation coordinates
- `R361S_post_all.rst7` – Post-translocation coordinates

---

# AMBER Input Files
Input files corresponding to each stage of the MD protocol.
- `min.in` – Minimization of reconstructed groups
- `md_solv.in` – Solvent dynamics
- `min1.in` – Side-chain minimization
- `min2.in` – Whole-system minimization
- `md-1.in` – Low-temperature equilibration (100K)
- `md-2.in` – Heating from 100K to 310K
- `md-3.in` – Unrestrained equilibration (310K)
- `md_equil.in` – Production MD simulations 

---

# MD Execution Scripts
Scripts used to execute simulations on HPC systems.
- `1_equilibration.sh` – Equilibration workflow
- `2_production.sh` – Production MD workflow

---

