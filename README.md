# Practical_Opsin_Vertebrates
Lecture_29_10_2025
Opsin Identification and Phylogenetic Analysis Pipeline

1. BLASTp Search on Ciona intestinalis
   - Open the Opsins.fasta file.
   - Copy one opsin sequence and perform a BLASTp search against Ciona intestinalis to identify potential opsin homologs.

2. Reverse BLAST for Identity Confirmation
   - Download the top Ciona sequences obtained from BLAST.
   - Perform a reverse BLASTp (using each Ciona sequence as a query) against the opsin database to confirm their identity as opsins.

3. Sequence Alignment
   - Copy the confirmed opsin sequences into the precompiled FASTA file (Opsins.fasta).
   - Open the file with AliView.
   - Align the sequences using MUSCLE.  https://www.ebi.ac.uk/jdispatcher/msa/mafft (copy paste)
   - Remove any sequences lacking the retinal-binding domain, as these are not true opsins.
   - Save it as a new .fasta  file.

4. Phylogenetic Model Selection and Analysis (IQ-TREE use ModelFinder to determine the best-fit substitution model)
     http://iqtree.cibiv.univie.ac.at/

5. Tree Visualization
   - Copy and paste the resulting tree into FigTree for visualization and editing.

Recommended Software
- Alignment Software:
  - AliView: http://www.ormbunkar.se/aliview/
  - MEGA: https://www.megasoftware.net/
- Phylogenetic Tree Viewer:
  - FigTree: https://tree.bio.ed.ac.uk/software/figtree/
