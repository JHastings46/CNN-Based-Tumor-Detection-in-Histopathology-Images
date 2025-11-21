## CNN Based Tumor Detection in Histopathology Images

This project uses Convolutional Neural Networks (CNNs) to classify tissue images as tumor or normal based on histopathology patches. The goal is to predict whether the center 32×32 region of each image contains tumor cells using real-world medical imaging data. The dataset contains over 277,000 .tif images and one CSV file with corresponding tumor/normal labels.
The pipeline covers data exploration, cleaning, model design, training, evaluation, and testing on unseen images.
A deeper CNN model achieved higher validation accuracy (76%) than the baseline (73%), showing that deeper layers capture more fine-grained tumor patterns.
Repository Includes:
- Data preprocessing and EDA
- CNN architecture comparison (Baseline vs Deep CNN)
- Hyperparameter tuning and training visualization
- Final test predictions on unseen image patches

Example output (probabilities of tumor presence):
- [0.681, 0.623, 0.745, 0.396, 0.743, 0.645, 0.421, 0.774, 0.268, 0.571]

**This notebook demonstrates how deep learning can help in early tumor detection using medical images while remaining interpretable and efficient for future real-world improvements.**
