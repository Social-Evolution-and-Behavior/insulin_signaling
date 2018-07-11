# insulin_signaling
This repository provides access to the data and methods used for the comparative analysis of ant brain gene expression between reproductive and non-reproductive castes. This work was originally published in Chandra, V., Fetter-Pruneda, I. _et al_. Science (2018):

**Social regulation of insulin signaling and the evolution of eusociality in ants**

Vikram Chandra\*(1), Ingrid Fetter-Pruneda\*(1), Peter R. Oxley(1,2), Amelia L. Ritger(1), Sean K. McKenzie(1,3), Romain Libbrecht(1,4), Daniel J. C. Kronauer(1)

1. Laboratory of Social Evolution and Behavior, The Rockefeller University, 1230 York Avenue, New York, NY 10065, USA
2. Samuel J. Wood Library, Weill Cornell Medicine, 1300 York Avenue, New York, NY 10065, USA
3. Department of Ecology and Evolution, University of Lausanne, Biophore Building, 1015 Lausanne, Switzerland
4. Institute of Organismic and Molecular Evolution, Johannes Gutenberg University, Johannes-von-Müller-Weg 6, 55128 Mainz, Germany

\* These authors contributed equally


## Table of contents

* [README](./README.md) - this file
* [License](./LICENSE) - GNU public license
* [DESeq2_output](./DESeq2_output) - the differential gene expression values calculated for each of the seven species using DESeq2.
* [orthomcl_output](./orthomcl_output) - the mcl groups from analysis of 18 NCBI-annotated insect genomes
* [comparative_analysis](./comparative_analysis.ipynb) - jupyter notebook showing the identification of concordant differentially expressed genes in seven ant species
* [Cpla_gene_lists](./Cpla_gene_lists) - the lists of ortholog groups for selected genes in Camponotus planatus
* [Orug_gene_lists](./Orug_gene_lists) - the lists of ortholog groups for selected genes in Odontomachus ruginodis
* [Cpla_contamination_removal](./Cpla_contamination_removal.ipynb) - jupyter notebook showing the pipeline to identify and remove contaminants from the Camponotus planatus transcriptome
* [Orug_contamination_removal](./Orug_contamination_removal.ipynb) - jupyter notebook showing the pipeline to identify and remove contaminants from the Odontomachus ruginodis transcriptome
* [clean_Cpla_txome](./clean_Cpla_txome.fasta) - Predicted peptide sequences for each transcript in the cleaned Camponotus planatus transcriptome
* [clean_Orug_txome](./clean_Orug_txome.fasta) - Predicted peptide sequences for each transcript in the cleaned Odontomachus ruginodis transcriptome
