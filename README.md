# Skin Cancer Classification Model Improvement

This repository showcases two distinct approaches to enhance the accuracy of a skin cancer classification model using the HAM10000 dataset. The two approaches involve the implementation of different strategies, namely using a focal loss function with a CNN model and upgrading the architecture to EfficientNetB7.

## Approach 1: Focal Loss Function with CNN (Convolutional Neural Network)

### Overview
In this approach, a Convolutional Neural Network (CNN) model was employed for skin cancer classification, utilizing the HAM10000 dataset. A focal loss function was incorporated to address the challenge of class imbalance within the dataset.

### Model Training
The CNN model was trained for 200 epochs, allowing it to learn intricate patterns in the skin cancer images. The training process resulted in a peak accuracy of 0.92111.

### Focal Loss Function
The focal loss function is designed to mitigate the impact of well-classified examples, focusing more on the difficult-to-classify instances. This helps improve the model's performance in scenarios where certain classes are underrepresented.

## Approach 2: EfficientNetB7 Integration

### Overview
In this alternative approach, the EfficientNetB4 architecture was substituted with the more complex EfficientNetB7. EfficientNetB7 is known for its superior efficiency in terms of accuracy and computational resources.

### Model Training
The EfficientNetB7 model was trained for an extended period of 400 epochs, allowing it to learn intricate features and patterns in the skin cancer dataset. This extended training led to a notable increase in accuracy, with the model achieving 0.93 as the highest accuracy.

### EfficientNetB7
EfficientNetB7 is a variant of the EfficientNet architecture, known for its scalability and efficiency. It achieves state-of-the-art results in various computer vision tasks with significantly fewer parameters compared to traditional models.

## Conclusion

Both approaches demonstrate effective strategies for improving the accuracy of a skin cancer classification model. The focal loss function addresses class imbalance, while the integration of EfficientNetB7 leverages a more advanced architecture, resulting in enhanced accuracy. Researchers and practitioners can explore and compare these approaches based on their specific requirements and resource constraints.

Feel free to explore the code in this repository to gain insights into the implementation details of each approach. If you have any questions or suggestions, please don't hesitate to reach out. 

Happy coding!


Realised by : BOUKTIB Salma, SAGHIR Aya and KHARBOUCH Hamza
