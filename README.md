# Autoencoder---Deep_CNN

## 🖼️ Deep CNN Autoencoder – Image Compression & Denoising

This project demonstrates the use of **Convolutional Neural Network (CNN) Autoencoders** for two key tasks:  
- **Image Compression** – reducing image size while preserving important features.  
- **Image Denoising** – removing noise from corrupted images to reconstruct clean outputs.  

## 📌 Project Information
An **autoencoder** is an unsupervised learning technique that learns efficient data representations (encoding) by training the network to ignore signal “noise.”  
Autoencoders can be applied to:
- Image compression  
- Image denoising  
- Feature extraction  
- In some cases, even **image generation**  

---

## 🔄 Flow of Autoencoder
Input Image -> Encoder -> Compressed Representation -> Decoder -> Reconstruct Input Image


- **Encoder**: Learns compressed latent representation of the input.  
- **Decoder**: Reconstructs the original image from the compressed representation.  

---

## ⚙️ Environment
- Jupyter Notebook
---

## 📚 Libraries Used
- `numpy` – numerical computations  
- `matplotlib` – visualization  
- `keras` – high-level neural network API  
- `tensorflow` – backend deep learning framework  

---

## 🧠 Neural Network Architecture
- **Convolutional Neural Network (CNN) Autoencoder**  
- Encoder: Convolution + Pooling layers to compress features  
- Decoder: Convolution + Upsampling layers to reconstruct images  
- Loss Function: Mean Squared Error (MSE) or Binary Crossentropy  
- Optimizer: Adam  

---

