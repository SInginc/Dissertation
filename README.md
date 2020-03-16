# MSc Dissertation at UoE

Main goal: Performance evaluation of two Virtual Screening (VS) tools (LIDAEUS and Autodock Vina). Based on the evaluation results, making attempts to improve the VS performance of LIDAEUS.

## A bit background

Virtual screening (**VS**) is a technique to select suitable molecules from a compound pool, which is widely used in the area of drug discovery and material science. According to the selection criteria, it can be divided into two groups, ligand-based VS (**LBVS**) and structure-based VS (**SBVS**). 

**LBVS** uses features extracted from existing compounds, which are the chemical structures or pharmacophore models. **SBVS** is to evaluate whether a compound is suitable in a constricted space (binding site). And this project was to evaluate the SBVS performance.

Strictly, the performance of an **SBVS** programme should be evaluated from three aspects, which are **docking power** (also called sampling power), **scoring power** and **ranking power** (also referred to screening power), respectively. 

**Docking power** and **scoring power** are the programme's capabilities to generate accurate ligand binding pose and corresponding affinity (normally, binding free energy), respectively. 

Generally, **ranking power** doesn't care about whether the programme can generate correct ligand poses or accurate affinities but only cares about the ranking orders of compounds resulting from the programmes (usually according to their affinities).

In this project, we only focused on the **ranking power** of the programmes.

## How to evaluate

Certainly, the feasibility of evaluating whatever power is dependent on the availability of experiment-validated data. For **docking power** and **scoring power**, things are much straigtforward because what we need are just the ligand-receptor co-crystals and the affinity numbers of the corresponding ligands. However, for **ranking power**, things become a bit more tricky.
