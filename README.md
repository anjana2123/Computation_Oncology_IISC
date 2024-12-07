# Dual-Target Pathways for Combined Anti-T2DM and Anti-Pancreatic Cancer Drug Effects

This repository presents a comprehensive study and computational model to identify dual drug targets for Type II Diabetes Mellitus (T2DM) and Pancreatic Ductal Adenocarcinoma (PDAC), which are interconnected diseases. The study integrates gene expression analysis, pathway enrichment, network construction, and influence propagation modeling to discover novel therapeutic pathways for combined treatment of both diseases.

## Key Contributions
- **Gene Expression Analysis:** Identification of common differentially expressed genes (DEGs) between T2DM and PDAC.
- **Pathway Enrichment:** Enrichment analysis revealed common pathways between both diseases.
- **Network Construction:** Constructed a 40-node pathway network with edge weights calculated based on gene overlap and significance.
- **Influence Propagation Model:** Simulated drug effects and influence spread across the network using edge weights, identifying the most influential pathways.
- **Drug Target Identification:** Focused on the most influential pathways such as focal adhesion, cell adhesion molecule binding, and hepatocyte growth factor receptor signaling.

## Project Structure
- **Data Collection:** Gene expression datasets from GEO (GSE20966) for T2DM and TCGA (RNA-seq) for PDAC.
- **Gene List Preparation:** Differentially expressed genes identified using GEO2R for T2DM and DEBrowser for PDAC.
- **Pathway Enrichment Analysis:** Top 40 pathways enriched across both diseases.
- **Network Model:** A 40-node pathway network used for simulating influence propagation.
- **Simulation Results:** Identified focal adhesion, cell adhesion molecule binding, and hepatocyte growth factor receptor signaling as key pathways influencing both diseases.

## Methods Overview
1. **Data Collection:** Gene expression datasets from GEO and TCGA.
2. **Differentially Expressed Genes (DEGs) Analysis:** Using online tools to identify upregulated and downregulated genes.
3. **Pathway Enrichment:** Performed using GSEA and ENRICHR, obtaining 40 significant pathways.
4. **Network Construction:** A network of 40 pathways was created based on shared genes, with edge weights determined by a custom formula.
5. **Influence Propagation:** Simulated drug effects and identified the top influential pathways using a series of simulations and epochs.

## Key Results
- **Most Influential Pathways:** Focal adhesion, cell adhesion molecule binding, and hepatocyte growth factor receptor signaling.
- These pathways are critical in both cancer progression and insulin resistance, making them promising targets for dual drug therapies.

## Conclusion
This study offers valuable insights into dual-target therapeutic strategies for patients suffering from both T2DM and PDAC. The integrated network and influence propagation model can help uncover more pathways for combined treatments, improving patient outcomes.

## Future Directions
- Further validation through experimental studies.
- Exploration of additional therapeutic strategies targeting the identified pathways.

## References
- **De Souza, A. et al.** "Diabetes Type 2 and Pancreatic Cancer: A History Unfolding." *Journal of Pancreas*, 2016.
- **Li, Y. et al.** "The relationship between pancreatic cancer and type 2 diabetes: cause and consequence." *Cancer Management and Research*, 2019.
- **Wang, F. et al.** "The relationship between diabetes and pancreatic cancer." *Molecular Cancer*, 2003.

## How to Use
Clone this repository:
   ```bash
   git clone https://github.com/yourusername/dual-target-pathways.git
