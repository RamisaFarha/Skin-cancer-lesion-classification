# Skin-cancer-lesion-classification

## Project Overview
This project aims to develop a Convolutional Neural Network (CNN) model to classify skin lesions using the **HAM10000** dataset, facilitating early skin cancer detection.

## Data Preparation
- **Training Set**: 8012 images
- **Test Set**: 2003 images
- **Preprocessing**: Images resized to 32x32 pixels and normalized.

## Model Training
- **Epochs**: 20
- **Loss Function**: Categorical cross-entropy
- **Optimizer**: Adam

## Performance Metrics
- **Final Test Accuracy**: 66.42%
- **Final Test Loss**: 0.8676

### Training Performance Highlights
- Accuracy improved from 57.70% to 69.09% over epochs.
- Validation accuracy fluctuated, indicating potential overfitting.

## Insights
- The model shows moderate accuracy, with room for improvement.
- Training accuracy increased consistently, while validation accuracy plateaued.

## Recommendations
1. Implement data augmentation techniques.
2. Explore transfer learning with pre-trained models.
3. Conduct hyperparameter tuning for optimization.

## Conclusion
The model achieved promising results in skin lesion classification, warranting further enhancement through advanced techniques.
