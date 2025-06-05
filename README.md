🌾 Microsoft-Rice-Leaf-Disease-Classification

In this project, we developed several deep learning models to classify rice leaf diseases using image-based diagnosis techniques.

Rice is a staple food for more than half of the world’s population, and timely identification of diseases in rice plants is crucial to ensure food security, especially in regions heavily dependent on rice farming. Leaf diseases significantly affect yield and quality, making early and accurate detection a priority for farmers and researchers.

This challenge provided a curated dataset containing high-quality annotated images of rice leaves across three categories:

Blast leaf

Brown leaf

Healthy leaf

The dataset included over 5,000 labeled images collected from experimental farms and agricultural research centers. The objective was to build a robust image classification model that could distinguish between these diseases and healthy rice leaves, enabling scalable, field-ready disease monitoring solutions.

We began with a baseline convolutional neural network (CNN) model and later fine-tuned state-of-the-art pretrained architectures including EfficientNet, ResNet50, DenseNet121, and Vision Transformers (ViT). We also applied data augmentation and test-time augmentation (TTA) to enhance the model's generalization capabilities.

The best-performing of our model achieved an accuracy of 90.75%.

You can find more details about the challenge on the official Microsoft Rice Leaf Disease Dataset page on Kaggle.

