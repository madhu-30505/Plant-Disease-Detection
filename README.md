# 🌱 Plant Disease Detection & Prevention

A deep learning-based application that identifies plant leaf diseases from images using **EfficientNetB0 and Transfer Learning**. The system predicts disease categories, displays prediction confidence, and provides relevant treatment and prevention recommendations through a web interface.

## ✨ Features

* Plant disease classification using deep learning.
* Supports corn, potato, and bell pepper leaf images.
* EfficientNetB0 with transfer learning.
* Image preprocessing and data augmentation.
* Disease prediction with confidence scores.
* Treatment and prevention recommendations.
* Image upload and live camera-based prediction.
* Web interface built using Flask.

## 🛠️ Tech Stack

Python | TensorFlow | Keras | EfficientNetB0 | OpenCV | NumPy | Pandas | Flask | HTML | CSS | JavaScript

## ⚙️ Workflow

1. Collect and organize plant leaf images.
2. Resize and preprocess images for model training.
3. Apply data augmentation to improve model generalization.
4. Use EfficientNetB0 for feature extraction and classification.
5. Train and fine-tune the model using transfer learning.
6. Predict the disease class and confidence score.
7. Display results and relevant recommendations through the web application.

## 🧠 Deep Learning Model

**EfficientNetB0** is a convolutional neural network (CNN) used for image classification. A pretrained ImageNet model is adapted to recognize plant disease categories using custom classification layers and transfer learning.

## 🌿 Supported Plant Categories

* **Corn:** Healthy, Common Rust, Gray Leaf Spot, Northern Leaf Blight
* **Potato:** Healthy, Early Blight, Late Blight
* **Bell Pepper:** Healthy, Bacterial Spot

*The supported categories depend on the dataset and model configuration used in the project.*

## 🚀 Getting Started

Clone the repository:

```bash
git clone <your-plant-project-repository-url>
cd <your-project-folder>
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open the local URL displayed in your terminal to access the application.

*Ensure that the trained model, class-label mapping, templates, and other required files are available at the paths expected by your application.*

## ⚠️ Limitations

* Prediction quality depends on the training dataset and image conditions.
* Similar disease symptoms may lead to incorrect classifications.
* Predictions should be verified before making important agricultural treatment decisions.
* Treatment recommendations should be checked against reliable agricultural guidance.

## 🔮 Future Improvements

* Support more crops and disease categories.
* Improve performance using larger, more diverse datasets.
* Deploy a mobile-friendly application.
* Add multilingual support for farmers.
* Improve recommendations using verified agricultural resources.

## 👩‍💻 Author

**Madhumitha M**
Computer Science and Engineering | Aspiring AI/ML Engineer

[GitHub](https://github.com/madhu-30505) | [LinkedIn](https://linkedin.com/in/madhu0505)
