# Project 2

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project 2 is due Monday, November 14 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/459156/assignments/5412724) in the Canvas assignment.

## Custom Handwritten Characters Dataset

The dataset you will be working with is available for download here:

* ["data_train.npy"](https://ufl.instructure.com/files/72621855/download?download_frd=1)
* ["labels_train.npy"](https://ufl.instructure.com/files/72621858/download?download_frd=1)
* ["data_test.npy"](https://ufl.instructure.com/files/72621555/download?download_frd=1)
* ["labels_test.npy"](https://ufl.instructure.com/files/72621857/download?download_frd=1)

## Files contained

1. training.ipynb ---- code used for training the datasets.
2. test.ipynb ---- code used for testing the datasets.
3. Project 2 - Dimentionality Reduction.ipynb ---- description of project 1
4. Model ---- contains all models generated from the training.ipynb.
5. Dataset ---- contains LDA, t-SNE and PCA components I get from question 3 and original dataset.
6. Project_1_report.docx ---- report in docx form
7. Project_1_report.pdf ---- report in pdf form
8. training.pdf ---- pdf form of training.ipynb
9. test.pdf ---- pdf form of test.ipynb
10. README.md ---- this file.

## How to use 

The models are in the Model file which is in my Google Drive, you need to down load from [here](https://drive.google.com/drive/folders/1YA2ljEgFa21XNYc-VkEGUdpImxp1wJi3?usp=share_link).

This file doesn't include 4 original dataset, so you need to load these data before running my code.  

Training: Training code do not need any parameters to input. It generates totally 10 models in file Model and 3 numpy arrays in file Dataset. And these models and data will be use in test code.     

Test: Test code has already loaded the datasets and resampled dataset, and all models have been loaded too. Except running all codes, you do not need any operation in Jupyter.
