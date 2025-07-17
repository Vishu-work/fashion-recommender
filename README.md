<h1 align="center">👗 Fashion Recommender System</h1>
<p align="center">
  A deep learning–powered visual recommendation engine built with <strong>TensorFlow</strong>. <br>
  Upload an image of a clothing item and get the top <strong>5 visually similar fashion recommendations</strong> instantly!
</p>

<p align="center">
  <img src="assets/banner.png" alt="Fashion Recommender Banner" width="80%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Framework-TensorFlow-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Model-ResNet50-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Task-Image_Similarity-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Recommendations-Top_5-orange?style=for-the-badge"/>
</p>

---

## 🧠 About the Project

The **Fashion Recommender System** helps users find visually similar clothes by analyzing their appearance using a **deep convolutional neural network**.

It uses a **pre-trained ResNet50 model** via **TensorFlow** to extract image embeddings and computes **visual similarity** using cosine distance.

> 🎯 **Goal**: Help users discover fashion items that match their style by returning the **Top 5 similar images** from a dataset.

---

## 🔍 How It Works

1. **Feature Extraction**: Each image is passed through **ResNet50** (without the top classification layer) to get a feature vector.
2. **Embedding Database**: All dataset images are preprocessed and stored as feature vectors.
3. **Similarity Search**: The uploaded image is converted to a feature vector and compared to others using **cosine similarity**.
4. **Top 5 Recommendations**: The 5 closest matches are displayed.

---



