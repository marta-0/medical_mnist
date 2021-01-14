# Medical images recognition - Medical MNIST analysis

The project focuses on Medical MNIST analysis. Models for image classification are developed, the results are looked into as well as some models performance visualisations are presented.

## Notebooks in the repository

* [Primary notebook](notebooks/Medical-MNIST.ipynb) - dataset analysis and preparation along with model training 
* [Results](notebooks/Medical-MNIST-results.ipynb) - metrics, lerning curves, violin plots, ROC and PR curves, images from outside the dataset
* [Occlusion sensitivity](notebooks/Occlusion-sensitivity.ipynb) - occlusion sensitivity for different models
* [t-SNE visualisations](notebooks/t-SNE-visualisations.ipynb) - mosaics, scatter plots and visualisations using RasterFairy

## Examples from each notebook
### Primary notebook

Average image of each class:

![average image of each class](https://deepdrive.pl/wp-content/uploads/2021/01/usredniony-obraz-dla-kazdej-z-klas.png)


### Results

ROC and PR curves for best model - different image sizes:

![pr and roc curves for best model - different image sizes](https://deepdrive.pl/wp-content/uploads/2020/12/najlepszy-model-32-px-1024x392.png)


### Occlusion sensitivity

Best model occlusion sensitivity for each class example:

![best model occlusion sensitivity for each class example](https://deepdrive.pl/wp-content/uploads/2020/12/best-model-occlusion-sensitivity-1024x554.png)


### t-SNE visualisations

t-SNE colored mosaic with images:

![tsne colorful mosaic](/images/tsne-images-mosaic-in-color.jpg)
