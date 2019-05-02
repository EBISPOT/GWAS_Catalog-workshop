# API demo

This is a really short demo on how the API workshop could go.

## Startup


### 1. If Python and Jupyter available on local machine

Clone repository to local folder. Start up jupyter notebook and open the workshop notebook.

```bash
git clone https://github.com/EBISPOT/GWAS_Catalog-workshop 
cd workshopDemo
jupyter notebook
```

### 2. If local Python or Jupyter not available

Publicly stored Jupyter notebooks can be uploaded and run on a remote server hosed by [Binder](https://mybinder.org/). The required Python packages are read from the `requirements.txt` file. Upon the first build the required packages will be installed subsequent startups will be faster. 

1. Go to [Binder](https://mybinder.org/)
2. For the github repository name provide this repository: `https://github.com/EBISPOT/GWAS_Catalog-workshop`
3. Path to a notebook file is `demo_1.ipynb`
4. Click `Launch`

After the first build a direct link can also be used to access the virtual environment: 
`https://mybinder.org/v2/gh/DSuveges/workshopDemo/master?filepath=demo_1.ipynb`

No modification will be saved in the repository, so ther's no need to be careful! :D 
