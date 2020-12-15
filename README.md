# ML Fall 2020 Final Project

Project Title: Multiclass Classification Task with Facial Recognition Application

Team:

Ashley Tsang <atsang5@jhu.edu>

Frederick Xu <fxu10@jhu.edu>

Jessica Su <jsu30@jhu.edu> 

Yusra Rahman <yrahman1@jhu.edu



Google drive link to the dataset: https://drive.google.com/drive/folders/1crhs7nqPADx95uzUjwc_ppZGHk_TXcuJ?usp=sharing

## Code for the Models

Since each of our baselines and methodologies have a lot of code individually, we kept them separate in different jupyter notebooks:

- `clustering_alg.ipynb` contains the code for running the agglomerative clustering method, as well as the associated visualization code
- `final_inception_model.ipynb` contains code for running InceptionNetV3
   - `inception_visualizations.ipynb` runs the code for output analysis
- `best_cnn.ipynb` contains the BestNN experimental method.

## npy files
- Since the data loading took quite a long time, we pickled the data files into `.npy` files for easier loading for later runs

## models files
- After training the models, the model results were pickled into `.model` files, located under the models/ directory.
- Visualizations for the clustering outputs are included in model_visualizations/
