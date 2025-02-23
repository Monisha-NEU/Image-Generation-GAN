# Image Generation using GANs

This project involves training a **Generative Adversarial Network (GAN)** to generate realistic images from the **CIFAR-10** dataset. The training process focuses on optimizing both the **Generator** and **Discriminator** using **Adam’s optimizer**, with evaluation based on **D loss** and **G loss** metrics.

## 🚀 Features
- Trained **Generator** and **Discriminator** using **Adam’s optimizer**.
- Evaluated performance using **D loss** and **G loss** metrics.
- Generated images at **every 100 intervals up to 1000 epochs** to track improvements in image clarity and quality.
- Controlled the **noise vector** for consistent evaluation of the Generator’s progress and to ensure diversity in image generation.

## 📌 Dataset
- **[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)**: A dataset containing **60,000** 32x32 color images across **10 classes**.

## 📂 Project Structure
