# weed-classifier
Repository for an image classification project based on the deepWeeds dataset. This was a course project for CS3244: Machine Learning at the National University of Singapore.

## Details
DeepWeeds is a dataset containing 17,509 images of 8 different weed species found in Australia, as well as non-weeds in the same geographical area. 

In this project, we attempted the following:
1. **Data Preprocessing** - dealing with the imbalanced data (undersampling, oversampling, SMOTE), and doing feature engineering (manually, and automatically using PCA/Autoencoders)
2. **Model Training** - Linear Models (KNN, SVM and Random Forests) and CNNs (from scratch with custom models, and also Transfer Learning with ResNet-50)
3. **Error Analysis** - Visualizing the results using a Confusion Matrix, GradCAM, looking at misclassified images etc.

For more details, check out the presentation slides [here](4.%20Presentation/Presentation%20Slides.pdf)
