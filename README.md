# Quantum-GAN-Prototype-for-Data-Augmentation-in-Sign-Language-Recognition

Overview
This repository contains a minimal Quantum Generative Adversarial Network (QGAN) built using PennyLane and PyTorch. It demonstrates how variational quantum circuits can be combined with classical discriminators to learn simple data distributions.

This is an educational prototype, developed to understand the principles of quantum machine learning (QML), with the long-term goal of applying quantum-enhanced data generation for sign language recognition.

Purpose
Disclaimer: This project is not intended for production use.
It is a basic experimental setup to explore the fundamentals of hybrid quantum-classical models.

I plan to utilize data augmentation techniques like this in my future work on sign language recognition with artificial intelligence. This prototype is a starting point for learning and experimentation.

Technologies
PennyLane (for quantum circuit simulation)

PyTorch (for classical components and training)

NumPy & Matplotlib (for data generation and visualization)

Supports both CPU and GPU execution (via Colab or local environment)

🧪 What This Project Does
Defines a simple 2-qubit quantum generator using angle embedding and entanglement

Uses a classical discriminator neural network

Trains the model using Wasserstein GAN with Gradient Penalty (WGAN-GP)

Learns to mimic a 1D Gaussian distribution

Visualizes real vs generated data throughout training

Example Output
During training, histograms are plotted showing how the generated distribution approaches the real one.

<!-- Replace or remove this line if you don't have images -->

# How to Run

# 1. Clone the repository
git clone https://github.com/yourusername/qgan-sign-language-prototype.git
cd qgan-sign-language-prototype

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the notebook or script
python train_qgan.py
Alternatively, open and run the project in Google Colab with GPU enabled.

📚 References
PennyLane QGAN Tutorials

WGAN-GP Paper

QML Literature for Image/Data Generation

💬 Future Plans
Extend to higher-dimensional data

Explore QGANs for real-world image augmentation

Apply to Turkish Sign Language (TİD) dataset generation
