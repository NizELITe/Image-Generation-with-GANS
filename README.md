# 🧑‍🎨 GAN for Face Generation
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)  
Generative Adversarial Network (GAN) implemented in TensorFlow/Keras to generate `64x64` grayscale face images from random noise.  

---

## 📂 Project Structure
- **Data Preprocessing** → Crop, resize, grayscale, normalize images  
- **Generator** → Transforms random noise into synthetic face images  
- **Discriminator** → Classifies real vs generated images  
- **Training Loop** → Adversarial training with checkpointing and image generation  
