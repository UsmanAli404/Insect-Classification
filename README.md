# 🐞 Insect Classification

This project is a deep learning-based **image classification system** designed to identify **10 different insect classes** using Convolutional Neural Networks (CNNs) and **MobileNetV3** as the base architecture. It achieves strong generalization performance and features a user-friendly interface for live predictions.

## 🧠 Overview

The model is trained to classify insects into the following categories:

- 🐝 Bees  
- 🪲 Beetle  
- 🦋 Butterfly  
- 🦟 Cicada  
- 🐉 Dragonfly  
- 🦗 Grasshoppers  
- 🦋 Moth  
- 🦂 Scorpion  
- 🐌 Snail  
- 🕷️ Spider  

Each class includes approximately **2,000 images**, giving the model a balanced dataset for learning.

---

## 📊 Performance

| Metric              | Accuracy |
|---------------------|----------|
| Training Accuracy   | 97%      |
| Validation Accuracy | 91%      |
| Testing Accuracy    | 91%      |

---

## 🗃️ Dataset

The dataset used in this project is based on the following Kaggle notebook:

🔗 [Kaggle Source](https://www.kaggle.com/code/vencerlanz09/insect-classification-using-cnn-mobilenetv3/input)

### 🔧 Preprocessing Steps

- Removal of corrupted and misclassified samples  
- Augmentation and resampling using an additional dataset to enhance model robustness  
- Image resizing and normalization to meet MobileNetV3 input requirements

## 🛠️ Tech Stack

- **Frameworks**: TensorFlow, Keras  
- **Model Architecture**: MobileNetV3 (transfer learning)  
- **Interface**: [Gradio](https://gradio.app/)  
- **Notebook**: Google Colab

## 🎯 Features

- ✅ **High Accuracy** insect classification  
- 🖼️ **Interactive Gradio Interface** for real-time predictions  
- 📈 **Visualizations** for sample training images, training history, class distributions, and confusion matrix and more  
- 🧹 Clean and well-commented Google Colab notebook for easy understanding and experimentation

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/UsmanAli404/Insect-Classification.git
   cd Insect-Classification
   ```

2. Open the `Insect_Classification.ipynb` in Google Colab.

3. Run all cells to:
   - Load and preprocess data  
   - Train the model  
   - Launch the Gradio interface  

## 🖼️ Sample Prediction UI

The Gradio interface lets you upload an image of an insect and instantly get the predicted class with confidence scores.

## 📌 Future Improvements

- Add support for more insect species  
- Improve accuracy on visually similar classes  
- Deploy as a web app using Streamlit or Flask  
- Use segmentation to detect insects within complex backgrounds

## 🤝 Acknowledgments

Thanks to the authors and contributors of the Kaggle dataset, and the open-source community for tools like TensorFlow, Keras, and Gradio.

## 📬 Contact

For questions or collaboration inquiries, feel free to reach out via [github](https://github.com/UsmanAli404/) or email: aottoman551@gmail.com.
