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

If you are using other OS than Linux please follow these instructions:

```
	conda create --name workshop python=3
	conda activate workshop
	conda install -c conda-forge keras
	conda install -c conda-forge tensorflow=2.0
	conda install -c conda-forge jupyter
	conda install -c conda-forge matplotlib
```

In some OSX it might be needed to add the following code at the beginning of the notebook:

```python
	import os
	os.environ[‘KMP_DUPLICATE_LIB_OK’]=‘True’
```

4. Activate environment

```
	conda activate workshop
```

5. Open Jupyter notebook and select autoencoder.ipyb 

```
	jupyter notebook
```


## Sessions

### Session 1

* We talk about the history of attention mechanisms in neural networks, and autoencoders (simple and VAE) using MNIST dataset.
	* Slides: `slides/Presentation_workshop_4.pdf`
	* Notebooks: `autoencoder.ipynb`, `autoencoder_answer.ipynb`, and `vae.ipynb`

### Session 2
* We talk about how the attention mechanims works, what are the query, key and value vectors?. We add attention to the VAE example using
keras attention layer. We implement a sentiment classifier using a custom layer for local addictive attention. 
	* Slides `slides/Presentation_workshop_session2.pdf`
	* Notebooks: `vae_cnn.ipynb`, `vae_cnn_attention.ipynb`, `vae_cnn_attention_answer.ipynb`, `2D_ae_simple_vs_attention.ipynb`, and
	`sentiment_classifier.ipynb`

### Session 3
-- To be added!


## Recomended links:
* [The illustrated transformer](http://jalammar.github.io/illustrated-transformer/)
* [Tensorflow transformer tutorial](https://www.tensorflow.org/tutorials/text/transformer)

