---
layout: single
permalink: /resources/
title: "Resources"
excerpt: "An open source, open science, and open data approach to better biomolecular force fields"
---

The Open Force Field Group makes a number of resources available to the community, including open source software, high-quality curated open datasets, and force fields.

---

## Publications
- [SMIRNOFF white paper](https://doi.org/10.1101/286542): This preprint/white paper introduces the SMIRNOFF format in the context of traditional force fields, explains the development and validation of our new small molecule force field smirnoff99Frosst, and highlights some directions the initiative is headed.

## Software

- [openforcefield](https://github.com/openforcefield/openforcefield): A python toolkit from the Open Force Field group for the development and use of modern molecular mechanics force fields based on direct chemical perception and parameterized with rigorous statistical methods. This also provides the SMIRNOFF force field format.
- [open-forcefield-tools](https://github.com/openforcefield/open-forcefield-tools): Development space for property calculation and force field parameterization tools.
- [SMARTY](https://github.com/openforcefield/smarty): A simple prototype implementation Bayesian atom type sampling using reversible-jump Markov chain Monte Carlo (RJMCMC) over SMARTS types. This also provides the SMIRKY tool, which samples over SMIRKS patterns for chemical perception of parameter types.

## Datasets

- [open-forcefield-data](https://github.com/openforcefield/open-forcefield-data): Curated datasets from the NIST ThermoML database to be used for force field parameterization.
- [MiniDrugBank](https://github.com/openforcefield/MiniDrugBank): A repository to track the creation and evolution of the MiniDrugBank Molecule set, filtered from [DrugBank Release Version 5.0.1](https://www.drugbank.ca/releases/5-0-1).

## Forcefields

- [smirnoff99Frosst](https://github.com/openforcefield/smirnoff99Frosst): The first general-purpose implementation of a SMIRKS Native Open Force Field (SMIRNOFF) as implemented by the SMIRNOFF `ForceField` class (in openforcefield.typing.engines.forcefield) for parameterizing small molecules for OpenMM and (via ParmEd and InterMol) a wide variety of other simulation packages.
