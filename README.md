# GWAS Catalog and Summary Statistics REST API Workshop

This repository contains training materials for the GWAS Catalog and Summary Statistics REST API workshop. This workshop provides examples on how to extract data from the GWAS Catalog for the most frequent use cases. For the complete documentation see API documentation: [GWAS Catalog REST API documentation](https://www.ebi.ac.uk/gwas/rest/docs/api) and [GWAS Catalog Summary Statistics REST API documentation](https://www.ebi.ac.uk/gwas/summary-statistics/docs/)

### Repository contents:

* **slides**: the REST API presentation materials
* **notebooks**: jupyter notebooks containing interactive code examples to demonstrate how to extract and parse data from the GWAS Catalog and the GWAS Catalog Summary statistics REST API. 

## Startup

### 1. If git and Jupyter available on local machine

Clone repository to local folder. Start up jupyter notebook and open the workshop notebook.

```bash
git clone https://github.com/EBISPOT/GWAS_Catalog-workshop 
cd GWAS_Catalog-workshop/notebooks
jupyter notebook
```
Then load the notebook of your interest.

### 2. If user has Google account

Via the Google account, a user can open the interactive notebooks on [google colab](https://colab.research.google.com) virtual machine.

Use the following links to start up virtual machines:

* [workshop_01](https://colab.research.google.com/github/EBISPOT/GWAS_Catalog-workshop/blob/master/notebooks/workshop_01.ipynb)

No modification will be saved in the repository, so there is no need to be careful! Have fun! 

### 3. Without google account

Publicly stored Jupyter notebooks can be uploaded and run on a remote server hosed by [Binder](https://mybinder.org/). The required Python packages are read from the `requirements.txt` file. Upon the first build the required packages will be installed subsequent startups will be faster. 

After the first build a direct link can also be used to access the virtual environment: 

* [workshop_01](https://mybinder.org/v2/gh/EBISPOT/GWAS_Catalog-workshop/master?filepath=notebooks%2Fworkshop_01.ipynb)

No modification will be saved, so there is no need to be careful! Have fun! 

## Available notebooks:

### workshop_01.ipynb

* Contains a short description of the returned data of the API. 
* Basic use-cases to fetch association data from the GWAS Catalog REST API and Summary Statistics API.

### gwas_cat_rest.ipynb

* Basic use-cases to fetch association data from the GWAS Catalog REST API

### sumstats_rest.ipynb

* Introductory exercise to the GWAS Catalog's summary statistics API.

## Links

* [GWAS Catalog REST API](https://www.ebi.ac.uk/gwas/rest/api)
* [GWAS Catalog REST API documentation](https://www.ebi.ac.uk/gwas/rest/docs)
* [GWAS Catalog Summary Statistics REST API](https://www.ebi.ac.uk/gwas/summary-statistics/api)
* [GWAS Catalog Summary Statistics REST API documentation](https://www.ebi.ac.uk/gwas/summary-statistics/docs/)

**Other readings:**

* Jupyter notebook tutorial: [link](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
* Binder documentation: [link](https://mybinder.readthedocs.io/en/latest/)
* Opening Jupyter notebooks hosted on github via Google colab: [link](https://medium.com/@steve7an/how-to-test-jupyter-notebook-from-github-via-google-colab-7dc4b9b11a19)

## Feedback

We would love to hear feedback from you! Please send your comments to [gwas-info@ebi.ac.uk](gwas-info@ebi.ac.uk)
