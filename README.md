# MelanomaCITResponse_scRNAseq_TILandPBMC_publication

This repository includes notebooks utilized to produce results for the publication "Myeloid-T cell interplay, cell state transitions and checkpoint inhibitor response in melanoma":

* Standard workflow (adapted from [besca 2.4](https://github.com/bedapub/besca), based on [scanpy](https://scanpy.readthedocs.io/en/stable/index.html))
* Cell annotation workflow (adapted from [besca 2.4](https://github.com/bedapub/besca), based on [scanpy](https://scanpy.readthedocs.io/en/stable/index.html), including exploratory analyses related to signature and marker gene expression
* Velocity analysis notebooks for CD8T cell, CD4 T cell and Monocyte-macrophages (based primarly on [scvelo](https://scvelo.readthedocs.io/en/stable/))
* Notebooks used to generate differential cell expression, differential cell abundance and the publication figures

The underlying count data can be retrieved from ArrayExpress, [E-MTAB-13770](https://www.ebi.ac.uk/biostudies/arrayexpress)

Additional intermediate data not included as supplementary material in the publication due to format restrictions are included in data/:
- Additional Table 1. Cell type frequencies, related to Figures 1-2.
- Additional Table 2. Ratios of cell-cell interactions, related to Figure 3.
- Additional Table 3. P-values of cell-cell interactions, related to Figure 3.
- Additional Table 4. Latent time estimations, related to Figure 6.
