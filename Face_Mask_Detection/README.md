## Face Mask Detection Using VGG16 and ResNet152

**dataset : https://www.kaggle.com/datasets/omkargurav/face-mask-dataset**

This project aims to develop a high-accuracy face mask detection system using two deep learning models, VGG16 and ResNet152. 
Both models are fine-tuned to detect masks in real-time, with ResNet152 achieving an accuracy of 98% and VGG16 achieving 97%.

### Steps
#### 1. Model Development and Training:
* Utilize VGG16 and ResNet152 as base models for face mask detection.
* Train both models on a comprehensive dataset of masked and unmasked facial images.

#### 2. Performance Comparison:
* Achieve a high accuracy rate in mask detection with both models.
* **ResNet152** :High accuracy of 98% in complex image recognition tasks, robustness to variations in lighting conditions, and suitabile for scenarios with large datasets.
  * Model Size: ResNet152 has a smaller size of approximately 232 MB.
  * Architecture: Deep residual network with 152 layers, allowing it to capture complex features in images.
  * Training Time: Longer training time due to its deeper architecture and higher complexity.
  * Potential Applications: Crowded environments (e.g., airports, train stations), low-light conditions (e.g., night-time surveillance).

* **VGG16** : Achieves a notable accuracy of 97%. Simplicity and ease of understanding, faster inference times, and lower computational requirements compared to ResNet152, making it suitable for small-scale deployments in various settings.
  * Model Size: VGG16 has a larger size of approximately 528 MB.
  * Architecture: Consists of 16 layers with simple convolutional blocks.
  * Training Time: Faster training time compared to ResNet152 due to its shallower architecture and lower complexity.
  * Potential Applications: Small-scale deployments in retail stores, offices, educational institutions.

#### 3. System Integration:
* Integrate the trained models into a real-time detection system.
* Implement efficient preprocessing and post-processing techniques to enhance detection speed and accuracy.

#### 4. Evaluation and Validation:
* Validate model performance using various metrics such as precision, recall, and F1-score.
* Conduct extensive testing in diverse environments to ensure robustness and reliability.

### Expected Outcomes:
* A highly accurate and reliable face mask detection system capable of real-time operation.
* Detailed comparative analysis of VGG16 and ResNet152 performance, highlighting the strengths and potential application scenarios for each model.
* Contribution to public health safety by ensuring higher compliance with mask-wearing guidelines through automated detection.
