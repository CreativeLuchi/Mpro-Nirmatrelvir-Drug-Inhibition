# Mpro-Nirmatrelvir-Drug-Inhibition
Comprehensive Structural and Functional Insights into SARS-CoV-2 Main Protease (Mpro) and its Inhibition by Nirmatrelvir: Sequence Conservation, Binding Mechanism, and Drug Efficacy Assessment.

A step-by-step guide covering the disease biology, key genes, drug discovery, and protein docking simulation to analyze approved drug- Nirmatrelvir.

🎯 Abstract
The SARS-CoV-2 main protease (Mpro, 3CLpro) is a critical enzyme for viral replication, making it a prime target for antiviral drug development. This mini research project integrates bioinformatics tools to characterize Mpro’s active sites, conserved regions, and inhibition by Nirmatrelvir, Mpro inhibitor. Sequence analysis revealed universal conservation of the catalytic dyad (Cys145-His41) and substrate-binding subsites across coronaviruses. Molecular docking demonstrated nirmatrelvir’s reversible covalent binding to Cys145, supported by interactions with key residues (His41, Glu166). ADMET predictions highlighted favorable pharmacokinetics but noted moderate CYP3A4-mediated metabolism and cardiac safety considerations. These findings provide mechanistic insights into Mpro’s role in COVID-19 and validate nirmatrelvir’s binding mode, emphasizing conserved regions as targets for broad-spectrum antivirals. The project highlights critical residues for substrate recognition and catalysis, investigates ADMET properties of Nirmatrelvir, and discusses structural factors contributing to its high binding affinity.


🎯 Materials and Methods
1. Data Acquisition
Protein Structure: Mpro (PDB ID: 6LU7) retrieved from the Protein Data Bank.
Ligand Structure: Nirmatrelvir (PubChem CID: 155903259) downloaded in SDF format.

2. Sequence Analysis
BLASTp: Performed against SARS-CoV-2 (taxid:2697049) using NCBI’s non-redundant protein database.
Multiple Sequence Alignment (MSA): Executed with Clustal Omega and visualized in Jalview to identify conserved residues.

3. ADMET Prediction
ADMET-AI: Predicted absorption, metabolism, and toxicity profiles using default parameters.

4. Molecular Docking
SwissDock: Automated docking of Nirmatrelvir to Mpro (default settings).
Visualization: PyMOL and ChimeraX used to analyze binding poses, hydrogen bonds, and hydrophobic interactions.

🎯 Software
BLAST, Clustal Omega, Jalview (sequence analysis).
SwissDock, PyMOL, ChimeraX (docking/visualization).
ADMET-AI (pharmacokinetic profiling).

🎯 Aims and Objectives This project aims to provide insights into:
1. Identification of conserved regions and catalytic residues in SARS-CoV-2 Mpro.
2. Mechanistic understanding of Nirmatrelvir inhibition: Why does the drug bind effectively?
3. Structural determinants of effective drug binding: Which amino acids are key for binding?
