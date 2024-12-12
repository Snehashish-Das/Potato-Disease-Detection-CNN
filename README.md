# Potato-Disease-Detection-CNN
Weekly Progress Repository for Group 3 in ML Practical Lab 

**ML Model**
- Model Type: Convolutional Neural Network (CNN) for image classification.

**Input Layer:**
- Images resized to 256x256 pixels and rescaled to [0, 1] range.

**Data Augmentation:**
- Random horizontal/vertical flips and rotations for better generalization.

**Convolutional Layers:**
- 6 Conv2D layers with ReLU activation for feature extraction.
- Kernel size: (3, 3) in each Conv2D layer.
- MaxPooling after each Conv2D to reduce spatial dimensions.

**Flatten Layer:**
- Flattens the 3D feature maps into 1D vectors.

**Fully Connected Layer:**
- 1 Dense layer with 64 units and ReLU activation.

**Output Layer:**
- Dense layer with 3 units (one per class) and softmax activation for multi-class classification.

**Loss Function:**
- Sparse Categorical Crossentropy, as the labels are integers (not one-hot encoded).

**Optimizer:**
- Adam optimizer for efficient training.
