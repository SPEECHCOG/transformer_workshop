# Instructions to run workshop code

1. Clone github repository

```
	git clone git@github.com:SPEECHCOG/transformer_workshop.git
```

2. If you do not have conda in your machine, plesas follow the instructions
on their website: [installing conda](https://docs.anaconda.com/anaconda/install/)

3. Install workshop environment

```
	conda env create -f workshop.yml
```

If you are using other OS than Linux please follow this instructions:

```
	conda creat --name workshop python=3
	conda activate workshop
	conda install -c conda-forge keras
	conda install -c conda-forge tensorflow=2
	conda install -c conda-forge jupyter
	conda install -c conda-forge matplotlib
```

4. Activate environment

```
	conda activate workshop
```

5. Open Jupyter notebook and select autoencoder.ipyb 

```
	jupyter notebook
```



