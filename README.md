
# Plant Disease Detection using CNN

This project demonstrates the use of a Convolutional Neural Network (CNN) to detect plant diseases using leaf images. It utilizes the Plant Village Dataset, which consists of over 61,000 images, and various augmentation techniques to improve the model's robustness.

## Dataset

- **Source**: [Plant Village Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1)
- The dataset contains **61,486 images** from 39 different categories of 16 plant species.
- **Augmentation techniques** applied:
  - Image flipping
  - Gamma correction
  - Noise injection
  - PCA color augmentation
  - Rotation
  - Scaling

## Model Architecture

The model is built using 9 Convolutional layers, each followed by the following components:
- **ReLU (Rectified Linear Unit)**: To introduce non-linearity.
- **Batch Normalization**: To stabilize and accelerate training.
- **Max Pooling**: To reduce dimensionality and extract important features.

### Model Summary
![Model Architecture](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/a8b844cf-6bc0-4ad2-9580-6702d9dfc012)

![Model Summary](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/b283cb1e-60ca-446b-bb4d-edb2254f31e1)

### Training and Data Split
- **Training set**: 80% of the dataset
- **Validation set**: 10% of the dataset
- **Testing set**: 10% of the dataset

### Training Configuration
- The model was trained for **10 epochs** with the use of data augmentation techniques to avoid overfitting and to improve generalization.

### Performance
- **Training accuracy**: 99.07%
- **Validation accuracy**: 97.53%
- **Test accuracy**: 96.94%

![Training Loss](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/41d95580-3a4d-4b65-99f1-e5caedf04caf)

![Loss Chart](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/06e6084c-1c17-4d52-a533-65e2773fae39)

### Confusion Matrix
The confusion matrix below illustrates the performance of the model on the test set, showing how often the classifier misclassifies each category.

![Confusion Matrix Heatmap](https://github.com/xecyborg/Plant-disease-detection-using-CNN/assets/103058112/bb58576f-ee1f-4925-94d6-d24599d5b782)

## References
- [Project Repository](https://github.com/manthan89_py/Plant-Disease-Detection)
- [Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1)
