# Deep Learning Medical Image Analysis Example

This project explores different convolutional neural network (CNN) models for image classification using the PneumoniaMNIST dataset. Three models with varying architectures were implemented and analyzed.

## 1. PneumoniaMNISTbb

### Model Architecture
- Input Layer
- Two Convolutional Layers (32 filters, 3x3 kernel, ReLU activation)
- Two MaxPooling Layers (2x2 pool size)
- Flatten Layer
- Output Layer (Dense, Sigmoid activation)

### Training Results
- Both accuracy vs epoch and loss vs epoch graphs intersect.
- Accuracy above training data, loss below training data.
- Achieves accuracy score of 1.0 and loss of 0.0.

## 2.2PneumoniaMNISTbb

### Model Architecture
- Input Layer
- Two Dense Layers

### Training Results
- Accuracy forms a straight line above training data.
- Loss is a curve below the training data.
- Achieves accuracy score of 1.0 and loss of 0.650.

## 3.2PneumoniaMNISTbb

### Model Architecture
- Input Layer
- Two Convolutional Layers (32 filters, 3x3 kernel, ReLU activation)
- Two Dense Layers

### Training Results
- Accuracy graph fluctuates but ends above training data.
- Loss is below the training data.
- Achieves accuracy score of 1.0 and loss of 0.04.

## Conclusion

After experimenting with three different models, it can be concluded that the third model (3.2PneumoniaMNISTbb) performs better compared to the first two. This conclusion is based on the increasing accuracy, decreasing loss, and achieving an accuracy score of 1.0 with a low loss of 0.04.

These observations indicate that the third model is more effective in learning the patterns from the PneumoniaMNIST dataset, resulting in accurate predictions.
