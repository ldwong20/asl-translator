# Creating datasets
In order to generate the `train`, `test`, and `val` diretories, you must run certain cells in `partition.ipynb`. Run the first cell to import all the required packages. For the ASL -> English task, then run the last two cells. For the GAN task, just run the second cell.

# Training models
## Fingerspelling -> English
Simply run all the cells of `train.ipynb` to train and evaluate the ResNet-18 and Inception-V3 models. 

## English -> Fingerspelling
Simply run all the cells of the `gan_trained.ipynb` to train and evaluate the GANs.

# Testing
## Fingerspelling -> English
Run `translte.ipynb` to trigger our live-webcam demo of Fingerspelling -> English translation.

## English -> Fingerspelling
Simply run all the cells of the `gan_trained.ipynb` to train and evaluate the GANs.
