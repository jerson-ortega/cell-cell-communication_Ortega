# Cell-to-Cell Communication Laboratory Activity

* **Student Name:** Jerson Lloyd T. Ortega
* **Activity:** Cell-to-Cell Communication Pathway Analysis (CD8+ Cytotoxic T Cell to Macrophage via IFNG)


 # Cell-to-Cell Communication: CD8+ Cytotoxic T Cell Signaling Pathway

## Title and Biological Question
* **Title:** Investigating Intercellular Signaling from CD8+ Cytotoxic T Cells to Macrophages via IFNG Signaling
* **Biological Question:** How do CD8+ cytotoxic T cells communicate via secreted signaling molecules to induce transcriptional and functional responses in target receiver cells during an immune response?

## Chosen Sender Cell and Biological Context
* **Sender Cell:** CD8+ cytotoxic T cell
* **Biological Context:** Immune activation during viral infection or anti-tumor defense. Activated CD8+ T cells coordinate immune responses by secreting effector cytokines to modulate neighboring immune and target cells.

## Candidate Ligand and Evidence for Sender-Cell Expression
* **Ligand / Signal:** IFNG (Interferon gamma)
* **Evidence:** Human Protein Atlas single-cell RNA expression data confirm that IFNG is group-enriched in T cells and natural killer (NK) cells, demonstrating that CD8+ cytotoxic T cells synthesize this protein.
* **Signaling Type:** Paracrine signaling

## Receptor and Receiver Cell with Supporting Evidence
* **Receptor:** IFNGR1 (Interferon gamma receptor 1) / IFNGR2 complex
* **Receiver Cell:** Macrophage
* **Supporting Evidence:** Human Protein Atlas and OmniPath annotations confirm that IFNGR1 acts as a transmembrane cell-surface receptor belonging to the interferon receptor family, expressed by cells like macrophages to receive extracellular cytokine signals.

## OmniPath Findings
* OmniPath intercell and annotation data classify IFNGR1 as a transmembrane receptor and cell surface marker. 
* Database records establish the molecular link for the intercellular communication axis between the T-cell derived ligand and its cognate surface receptor.

## STRING Network Interpretation
* **Network Components:** IFNG, IFNGR1, JAK1, JAK2, STAT1
* **Network Stats:** 5 nodes, 10 edges, and a PPI enrichment p-value of 3e-5, indicating significantly more interactions than expected by chance.
* **Enriched Pathway:** Type II interferon-mediated signaling pathway and cell surface receptor signaling via the JAK-STAT pathway.
* **Key Downstream Proteins:** JAK1, JAK2, and STAT1 bridge receptor activation to intracellular transcriptional changes.

## IntAct Validation
* **Interacting Pair:** IFNG (UniProt ID: P01579) and IFNGR1 (UniProt ID: P15260)
* **Experimental Evidence:** IntAct curated records confirm physical association and direct protein-protein interactions validated through experimental methods such as x-ray diffraction, solid phase assays, and co-immunoprecipitation.

## Final Model and Interpretation
<img width="1984" height="2120" alt="34445" src="https://github.com/user-attachments/assets/710eacbc-581d-493d-b449-e11f7be6a0c6" />

> In this cell-to-cell communication model, the CD8+ cytotoxic T cell acts as the sender cell, synthesizing and secreting the cytokine interferon-gamma (IFNG) during an active immune response. IFNG travels via paracrine signaling through the extracellular space to bind to the IFNGR1/IFNGR2 receptor complex expressed on the surface of a receiver cell, such as a macrophage. Database annotations from OmniPath confirm the ligand-receptor pairing, while Human Protein Atlas data support expression profiles in these respective cell types. Upon ligand binding, receptor oligomerization triggers downstream intracellular signaling mediated by Janus kinases (JAK1 and JAK2) and signal transducer and activator of transcription 1 (STAT1), as mapped in the STRING functional network. Experimental evidence from IntAct validates the physical binding and interaction mechanics between these pathway proteins. Ultimately, nuclear translocation of phosphorylated STAT1 drives the transcription of interferon-stimulated genes, resulting in enhanced antigen presentation, antimicrobial defense, and heightened cellular activation in the receiver cell. This integrated multi-database approach bridges extracellular recognition with intracellular transcriptional responses.

## References and Database Links
* Human Protein Atlas: https://www.proteinatlas.org/
* OmniPath Explorer: https://explore.omnipathdb.org/
* STRING Database: https://string-db.org/
* IntAct Molecular Interaction Database: https://www.ebi.ac.uk/intact/
* UniProt: https://www.uniprot.org/
  
