# BrainTumourDetection


This project uses deep learning to detect brain tumors in medical images. The project is designed to classify whether a brain tumor is present or not. We built a model using convolutional layers, maxpooling, and dense layers, and also used the VGG16 pre-trained model for comparison.

<b>Dataset</b>
<br>
<br>
We used the Brain MRI Images for Brain Tumor Detection dataset from Kaggle, which contains MRI images of the brain with and without tumors. The dataset consists of 253 images, of which 155 images contain tumors and 98 images are without tumors. We preprocessed the data by resizing the images to 224 x 224 pixels and applying normalization to the pixel values.

<strong>Model Architecture</strong>
<br>
<br>
We built a custom convolutional neural network (CNN) model with 3 convolutional layers, 3 max pooling layers, and 2 dense layers. We also used the VGG16 pre-trained model for comparison. Both models use ReLU activation functions and the Adam optimizer with a binary cross-entropy loss function.

<strong>Training and Validation</strong>
<br>
<br>
We trained both models for 10 epochs with a batch size of 32. We used an image data generator with a 70/30 split for training and validation. We also used the accuracy and binary cross-entropy loss as validation metrics.

<strong>Results</strong>
<br>
<br>
The custom CNN model achieved an accuracy of 91% and a binary cross-entropy loss of 0.128 on the validation set. The VGG16 model achieved an accuracy of 82.35% and a binary cross-entropy loss of 0.224 on the validation set. The custom CNN model outperformed the VGG16 model in terms of accuracy and loss.
