#  VisionCraft – Image Classification with CNN on CIFAR-10

**VisionCraft** is a deep learning project built using TensorFlow/Keras to classify images from the CIFAR-10 dataset into 10 categories like airplane, cat, truck, dog, and more. It leverages a custom Convolutional Neural Network (CNN) trained on thousands of labeled images to build computer vision capabilities from scratch.

---

##  Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- CIFAR-10 Dataset (from `keras.datasets`)

---

##  Model Highlights
- 3 Convolutional Layers
- MaxPooling after each conv layer
- Dropout for regularization
- Fully Connected Layers with Softmax
- Trained on 50,000 images across 10 classes

---

##  Results

| Metric          | Value     |
|-----------------|-----------|
| Final Accuracy  | ~70%      |
| Validation Acc  | ~68%      |
| Epochs          | 10        |
| Batch Size      | 64        |

<img src="images/performance_plot.png" width="600">

---

##  Dataset
CIFAR-10: 60,000 32×32 color images across 10 classes

---

##  Setup Instructions

```bash
git clone https://github.com/YOUR_USERNAME/VisionCraft.git
cd VisionCraft
pip install -r requirements.txt
