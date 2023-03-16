# Purification and characterization of human neural stem and progenitor cells
This project contains datasets related to the publication "Purification and characterization of human neural stem and progenitor cells." Method details can be found in the paper, referenced below.

The `h5ad` file and the accompanying Jupyter notebook can be downloaded from Synapse [here](https://www.synapse.org/#!Synapse:syn51201773/). The dataset contains 9,454 single-cell transcriptomes sequenced using Smart-seq2 or Smart-seq3, along with accompanying metadata.

## Metadata description
The meatdata is contained within the `.obs` view of the `AnnData` object. It contains the following entries:
* `SequencingRun`: identifier for the sequencing run; used for batch correction.
* `SampleID`: identifer for the tissue donor.
* `SampleType`: type of tissue from which cells were collected.
* `age`: age of tissue donor. GW, gestational week.
* `sex`: sex of tissue donor. M for male, F for female, U for unknown.
* `tissue`: specific tissue region from which cells were isolated. "Whole brain" for unknown region.
* `96plate`: numerical identifier for the 96-well plate into which the cell was originally sorted.
* `96plateloc`: the well number of the 96-well plate into which the cell was originally sorted.
* `384plate`: identifier for the 384-well plate into which the cell's cDNA was transferred for tagmentation reactions.
* `384loc`: the well number of the 384-well plate into which the cell's cDNA was transferred.
* `barcode`: cell barcode added following tagmentation during gap repair enrichment PCR.

Citation: Liu, D.D., He, J.Q., Sinha, R., Eastman, A.E., Toland, A.M., Morri, M., Neff, N.F., Vogel, H., Uchida, N., and Weissman, I.L. (2023). Purification and characterization of human neural stem and progenitor cells. Cell 186(6).
