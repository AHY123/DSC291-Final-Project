# More Comprehsneive Motif Databse for Gene Regulatory Network

While larger and more comprehensive motif databases theoretically improve the identification of transcription factors (TFs) affecting gene expression, significant challenges remain. One challenge is the variety of databases available, with different databases tailored to specific organisms such as humans and mice. Popular examples include HOCOMOCO and JASPAR, which are widely used but may differ in the range and accuracy of their motif collections. Another challenge is database coverage. Newer tools like SCENIC+ claim to curate and cluster the most comprehensive motif collection, boasting over 30,000 motifs to enhance the TF identification (Bravo González-Blas et al., 2023). We hypothesize that the motif database provided by SCENIC+ will enable the identification of a greater number of TFs that significantly influence gene expression compared to databases like HOCOMOCO. By comparing the performance of these databases, we aim to evaluate whether SCENIC+ offers a measurable improvement in GRN prediction accuracy and transcription factor identification.

## Environment

Please refer to the [Dictys](https://github.com/pinellolab/dictys?tab=readme-ov-file#option-1-with-anaconda) Github Page to install the environment first. 

## Motif Threhold Calculation

Here is the [method](motif_convert/treshold_calculator.py) help to calculate the threshold of a given motif matirx.

Here is the [method](motif_convert/convert_into_motif.py) help to convert the scenic+ nmotif databse into the format of .motif.

Here is the [method](motif_convert/motif_uncapitalize.py) help to uncapitalize the motif name in the database to be compatible withsome particualr nomenclature.

## Run Gene Regulatory Network

Please refer to this [notebook](full_tutorial_notebooks/1-data.ipynb) to know how to prepare for the data. 

Please refer to this [notebook](full_tutorial_notebooks/2-makefile.ipynb) to know how to set up Makefile.

Please refer to this [notebook](full_tutorial_notebooks/3-static-inference.ipynb) to know how run the whole GRN.

Please refer to this [notebook](full_tutorial_notebooks/4-static-analysis.ipynb) to know to get the data.

## Reference

Dictys: dynamic gene regulatory network dissects developmental continuum with single-cell multiomics Nature Methods (2023)

Github Page: https://github.com/pinellolab/dictys/tree/master