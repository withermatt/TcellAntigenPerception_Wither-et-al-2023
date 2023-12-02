# antigen_perception_tcells

R code for reproducing all analyses used in Wither et al. Antigen perception in T cells by long-term Erk and NFAT signaling dynamics. PNAS 2023.

.zip files contain relevant data used for reproducing our results:
  1. "Quantified_cell_objects" is the output from MATLAB containing activity measurements for Erk and NFAT derived from translocation reporters.
        - "BULK" indicates cells are not tracked
        - "SC" indicates cells that are manually tracked and validated across timepoints.
        - The column named "track" indicates the unique cell identities
          
  2. "analysis_objects" is a set of intermediate R objects generated throughout the analysis of this entire study. These objects contain the analyzed data and results that are presented in the figures of the paper.
  3. "CD69" is the CD69 expression data exported from FlowJo.
  4. "PD_1_CD25_Data" is the PD1 and CD25 expression data exported from FlowJo and generated by our mathematical models.


