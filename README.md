# 👗 FashionSense-CNN

**FashionSense-CNN** is a deep learning project that uses a Convolutional Neural Network (CNN) to classify fashion items from the Fashion MNIST dataset. It includes a Flask web app for users to upload images and get real-time predictions of clothing categories like T-shirts, dresses, sneakers, and more.

---

## 🧠 Project Overview

- 📚 **Dataset**: [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)
- 🧠 **Model**: Convolutional Neural Network (CNN)
- 🖥️ **Frameworks**: TensorFlow, Keras, Flask
- 🌐 **Frontend**: HTML (via Flask templates)
- 📦 **Deployment**: Localhost (Flask app)

---

## 🧪 Demo

Upload a fashion item image (28x28 grayscale), and the app will classify it as one of the 10 categories:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

---

## 📁 Repository Structure

| File/Folder             | Description                                  |
|--------------------------|----------------------------------------------|
| `Fashion_MNIST_CNN.ipynb`| Jupyter notebook with model training code     |
| `my_model.hdf5` *(manual)* | Trained CNN model (must be saved manually) |
| `app1.py`               | Flask backend for prediction                  |
| `templates/index.html`  | Web page to upload image                      |
| `templates/result.html` | Web page to display prediction                |

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/FashionSense-CNN.git
cd FashionSense-CNN
