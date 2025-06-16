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
1. BLAST, Clustal Omega, Jalview (sequence analysis).
2. SwissDock, PyMOL, ChimeraX (docking/visualization).
3. ADMET-AI (pharmacokinetic profiling).

🎯 Aims and Objectives This project aims to provide insights into:
1. Identification of conserved regions and catalytic residues in SARS-CoV-2 Mpro.
2. Mechanistic understanding of Nirmatrelvir inhibition: Why does the drug bind effectively?
3. Structural determinants of effective drug binding: Which amino acids are key for binding?

🎯 Result files attached

1. Multiple Sequence Alignment
   
![Screenshot 2025-06-13 at 22 14 36](https://github.com/user-attachments/assets/9a8a71a1-1af3-4055-a38a-59129a010627)
![mpro jalview MSA](https://github.com/user-attachments/assets/3003ae37-38b8-4998-8da0-278f7848d2fc)
![image 1](https://github.com/user-attachments/assets/fc5eddb0-5060-4c53-bbeb-715823a52756)
![Screenshot 2025-06-13 at 12 50 27](https://github.com/user-attachments/assets/d79ce590-75df-4179-9adc-ab6b2bda3a7a)

Explanation: To evaluate the conserved regions of SARS-CoV-2 main protease MPro and assess the evolutionary robustness of its inhibitor binding site, I performed both Pairwise Sequence aligmet using blastp and multiple sequence alignment (MSA) using representative sequences from various SARS-CoV-2 lineages and related coronaviruses. The resulting alignment revealed a high degree of sequence conservation, particularly within the catalytic dyad and substrate-binding regions (S1 & S2). Critical residues involved in Nirmatrelvir binding, including His41, Cys145, Glu166, and Met165, were strictly conserved across all sequences analyzed. This strong conservation suggests that Mpro maintains a structurally constrained active site annd substrate binding iste making it an ideal target for antiviral drug development. The original Fasta Files attached https://github.com/CreativeLuchi/Mpro-Nirmatrelvir-Drug-Inhibition/tree/main/MPro-Nirmatrelvir%20Results



2. Molecular Docking and Visualization

![surface docking view](https://github.com/user-attachments/assets/ceb0fd14-56f7-4cd2-b63d-f146a3cba00d)
![Cartoon view docking](https://github.com/user-attachments/assets/dc49c08f-0a88-40fb-90b4-ac015d6bf3f7)
![Binding site](https://github.com/user-attachments/assets/27af2034-f27b-485c-9c80-e3d0d23a9dd8)
![Active site-ligand docking](https://github.com/user-attachments/assets/5ac4d0a3-cf4b-4366-85ed-39eb599357d6)

Explanation: Docking identified Nirmatrelvir as a potent inhibitor of viral replication as seen in the results above. The ligand was found to occupy the region adjacent to the His41-Cys145 catalytic dyad, effectively mimicking substrate binding. The ligand formed key hydrogen bonds with conserved residues including Glu166, His163, and Gly143. These results suggest a potent inhibitory mechanism based on competitive binding and steric blockade of substrate access to the catalytic site. Combined with sequence conservation analysis, these findings support Nirmatrelvir's potential as a key ligand against SARS-CoV-2. The original Files attached https://github.com/CreativeLuchi/Mpro-Nirmatrelvir-Drug-Inhibition/tree/main/MPro-Nirmatrelvir%20Results


3. Ligand Identification and ADMET Prediction

![ADMET result table_page-0002](https://github.com/user-attachments/assets/4eaf43af-9e85-44fe-bce3-feacb10b06d5)
![ADMET result table_page-0001](https://github.com/user-attachments/assets/cb609f8a-9686-466f-bf3a-f90cb77affda)


The compound Nirmatrelvir PubChem CID (155903259) has moderate molecular weight and balanced lipophilicity, with good potential to cross the blood-brain barrier. It follows most drug-likeness rules but shows some Lipinski violations, which may affect oral bioavailability. The compound is primarily metabolized by CYP3A4, so drug interactions via this enzyme should be considered. Toxicity predictions are generally low to moderate risks, with a medium level cardiac toxicity (hERG- 0.5546). Absorption is predicted to be high in humans, though Caco-2 permeability (–5.28) is a moderate permeability result — not ideal, but not poor which suggest possible variability. The compound has moderate solubility, which may affect formulation and bioavailability. These parameters suggest it is a promising molecule with typical drug-like properties but may require optimization to improve bioavailability and minimize potential cardiac risk. The original Fasta Files attached https://github.com/CreativeLuchi/Mpro-Nirmatrelvir-Drug-Inhibition/tree/main/MPro-Nirmatrelvir%20Results






   
