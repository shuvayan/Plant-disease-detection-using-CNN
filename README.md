# Plant-disease-detection-using-CNN
- A 5 layer CNN model to detect plant disease using leaf images.

## Dataset
- The model is trained on [Plant Village Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1).
- The dataset has  61,486 images of total 39 categories of 16 variety plants and backgrounds.
- The dataset has been augmented using different techniques like image flipping, Gamma correction, noise injection, PCA color augmentation, rotation, and Scaling.

## Model
- The model consisted of 9 Convolutional layers followed by ReLU, Batch Normalization and Max Pooling.
  ![model_architecture](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/a8b844cf-6bc0-4ad2-9580-6702d9dfc012)
  
  ![model_summary](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/b283cb1e-60ca-446b-bb4d-edb2254f31e1)

- 80% of dataset has been used for training, 10% for validation and 10% for testing.
- The model has been trained for 10 epochs.
  ![loss](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/41d95580-3a4d-4b65-99f1-e5caedf04caf)
  
  ![loss_chart](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/06e6084c-1c17-4d52-a533-65e2773fae39)

- The accuracy of the model on **training set is 93.07%, validation set is 91.53% and test is 90.94%.**
  ![heatmap](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/bb58576f-ee1f-4925-94d6-d24599d5b782)

- References:
- [Project](https://github.com/manthan89_py/Plant-Disease-Detection)
- [Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1)
