# Code to accompany the paper ‘Projection of climate and technology impacts on crops key to food security'

# MAR-X model

A parsimonious multivariate autoregressive model to project the impact of climate change on agricultural production, with a time-dependent intercept term to model the changing rate of technological advancement.


## Directory Structure

The directories in this repo are as follows:

QuickAgri_marx.ipynb

* The Jupyter notebook contains the training and projection processes for the MAR-X model and the model selection approach. An example of using the wheat dataset to train the MAR-X model and then employing it to make projections is provided. In addition, the model selection process for wheat is illustrated. Based on this code, it is possible to experiment with other crops selected by the readers. 

./inputs/

* Contains dataframes used to train the MAR-X model and time series of climate variable projections generated from CMIP5 models, which are used to project future crop production. 


## License

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
