
# Improving Enhancer Identification with a Multi-Classifier Stacked Ensemble Model

This repository contains the implementation of a machine learning approach aimed at improving **enhancer identification** using a **multi-classifier stacked ensemble model**. Enhancers are regulatory regions in DNA that play a crucial role in gene expression and cell identity. Identifying enhancers is essential for understanding gene regulation and the mechanisms behind various cellular processes.

The proposed model combines multiple classifiers in a stacked ensemble method to improve the accuracy of enhancer identification from genomic data.

## Key Steps

### 1. Feature Generation
Run the **`Create_feature_Descriptors.ipynb`** file to generate the features for both the training and testing datasets. This notebook prepares the input data required for training and testing the classifiers.

### 2. Model Training
Run the **`Models_Training.ipynb`** file to train the model. This script will train multiple classifiers and save the best parameters for each classifier, which will be used for final evaluation.

### 3. Model Testing
Finally, run the **`Models_Testing.ipynb`** file to evaluate the performance of the model using the test dataset. This script will display the results and performance metrics of the stacked ensemble model.

## Citation
If you use this work in your research, please cite the following paper:

@article{mir2023improving, title={Improving enhancer identification with a multi-classifier stacked ensemble model}, author={Mir, Bilal Ahmad and Rehman, Mobeen Ur and Tayara, Hilal and Chong, Kil To}, journal={Journal of Molecular Biology}, volume={435}, number={23}, pages={168314}, year={2023}, publisher={Elsevier} }
