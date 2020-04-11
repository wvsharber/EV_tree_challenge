# EV Tree Masking Challenge

This repo contains Python code (mostly in Jupyter Notebooks) exploring the use of machine learning to automatically mask trees from aerial photographs. 

There are three accompanying blog posts about this project, two discussing the results presented in the final, explanatory notebook (see below for location). [Part 1](https://medium.com/@wvsharber/detecting-trees-in-aerial-photography-part-1-1c8e4b4cc955) discusses the development of the labeled training data from the raw data. [Part 2](https://medium.com/@wvsharber/detecting-trees-in-aerial-photography-part-2-ef096587a047) details how I used a random forest approach for the image segmentation problem of masking trees from the aerial image. Finally, [part 3](https://medium.com/@wvsharber/labelme-image-annotation-for-geotiffs-b460ba83804f) explores a potential manual alternative to developing the training data using the Labelme image annotation software. 

### Guide to this Repo
In the `data/` directory holds instructions to download the training and evaluation data and pickle files for the models and dataframes.

The `notebooks/` directory holds experimental code in the `exploratory/` directory and a final, explanatory notebook in the `final/` directory. 

The `reports/` directory contains figures and graphs.

To set up the conda environment necessary to install the packages for using the notebooks, run the following code from inside the cloned repo:

```conda env create -f environment.yml```