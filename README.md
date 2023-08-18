
# Bird Species Classification using InceptionV3 and Transfer Learning
# Collaborators:
- Abdullah
- Ivan
# Introduction:
The evolution of deep learning, specifically Convolutional Neural Networks (CNN), has significantly enhanced the capabilities of image classification. This project focuses on leveraging the InceptionV3 architecture, combined with transfer learning, to classify various bird species. By harnessing the strengths of this methodology, we aim to achieve high accuracy in bird species recognition.

# Dataset:
The dataset utilized in this project consists of images from various bird species. We've narrowed our focus to a subset of these species, specifically:

- Total Images: 2526
- Training Images: 2376 (belonging to 15 classes)
- Validation Images: 75 (belonging to 15 classes)
- Test Images: 75 (belonging to 15 classes)
# Model:
Our endeavor in bird species classification employed the InceptionV3 architecture, fine-tuned for our specific classification task. The primary facets of our model include:

- Base Model: InceptionV3 pre-trained on the 'imagenet' dataset.
- Custom Top Layers: These layers, added onto the base model, consist of a GlobalMaxPooling2D layer, Dense layers, and a Dropout layer for regularization. The final layer employs a softmax activation function for multi-class classification.
# Model Training and Performance:
Our model underwent a rigorous 10-epoch training regimen. Here's a summary of its performance:

- Epoch 1: Training accuracy: 76.32%, Validation accuracy: 96.88%
- Epoch 2: Training accuracy: 94.84%, Validation accuracy: 98.44%
- ...
- Epoch 9: Training accuracy: 98.51%, Validation accuracy: 98.44%
- Epoch 10: Training accuracy: 98.82%, Validation accuracy: 100%
Upon evaluation, our model achieved a perfect score:

- Test Accuracy: 100%
# InceptionV3's Strengths:
The success of the InceptionV3 model in our task can be credited to various aspects:

- Architecture: InceptionV3's unique architecture allows it to efficiently capture features from images.
- Transfer Learning: By utilizing a model pre-trained on the extensive 'imagenet' dataset, we can harness the generalized features it learned and fine-tune them for our specific task.
- Custom Layers: The added layers enable the model to further specialize in the classification of our specific bird species.
# Conclusion:
Our bird species classification task, employing the InceptionV3 model combined with transfer learning, has culminated in a model with exemplary accuracy. Achieving a perfect test accuracy of 100% attests to the model's robustness and precision in identifying various bird species.

The InceptionV3 model, with its intricate architecture, coupled with transfer learning, has showcased an unparalleled performance in our task. These results affirm the potential and efficacy of utilizing advanced deep learning architectures in specialized classification tasks.

# Dive Into The Code:
For a better understanding of our methodology, we encourage you to delve into the provided Jupyter Notebook within this repository. The notebook elucidates each step, from data processing to model evaluation, in detail.

Should you have any inquiries or feedback regarding our project, please don't hesitate to reach out. We hope our venture piques interest and catalyzes further exploration in the vibrant domain of deep learning for image classification.

Thank you for your engagement with our project!
