# Functional analysis of single-cell transcriptomics

Recent advances in omics technologies have led to a rapid increase in the popularity and applications of single-cell data-sets. Standard analyses and workflows solely focus on basic preprocessing steps followed by the identification of differentially expressed genes, and their subsequent use in cell-type annotation and characterization of biological processes. In this tutorial, we show how prior knowledge can be used to extend each of the aforementioned steps, as well as to extract clear biological insights. Furthermore, we provide an introduction to the state-of-the-art intercellular communication methods, as tools for systems-level hypothesis generation tools in single-cell data. We thus cover a diverse set of prior knowledge resources and show how these can be used to support and extend analysis steps ranging from quality control, cell-type annotation and transcription factor and cytokine activity inference. Finally, we show how advanced functional omics analyses can be used to refine cell-cell communication predictions.

## 1. Single-cell processing, enrichment and footprint analysis

### Instalation
To install the python dependencies run:

```
# install mamba (faster than conda)
pip install mamba
# create an environment with the necessary packages
mamba env create -f scanpy_env.yml --name scanpy
# activate the environment
conda activate scanpy
# add environment as kernel for jupyter-lab
python -m ipykernel install --user --name=scanpy --display-name='scanpy'
```

Then to start working run:
```
jupyter-lab
```

## 2. Cell-cell comunication inference and linking to downstream events

### Installation
```
mamba create -n seurat -c conda-forge -c bioconda r-seurat=4*
```

Then to start working run:
```
rstudio
```
