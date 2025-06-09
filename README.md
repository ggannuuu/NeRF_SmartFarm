# 🧠 Neural Radiance Fields (NeRF) on Blender Dataset

This repository contains an implementation of a **Neural Radiance Field (NeRF)** using the Blender dataset, designed for high-fidelity novel view synthesis of 3D scenes. NeRF is a cutting-edge technique in computer vision that learns 3D scene geometry and appearance from 2D images using deep neural networks.

> 🛠️ This project was developed as part of my research in robotics and autonomous systems, showcasing my ability to work at the intersection of computer vision, optimization, and software engineering.

---

## 🚀 Project Highlights

- ✅ Implements a full NeRF pipeline using PyTorch  
- 📸 Renders photo-realistic novel views from sparse input images  
- 📦 Supports training and testing on the Blender synthetic dataset  
- 🧪 Includes tools for visualization and model evaluation  
- 🧱 Modular structure for easy experimentation with model components  

---

## 🧰 Technologies Used

* The model training and image generation were done in Google Colab

- Python 3.12  
- PyTorch  
- NumPy  
- Matplotlib  
- Blender Dataset (from original NeRF paper)  

---

## 📁 File Overview

- `NERF_Blender.ipynb` – Main Jupyter Notebook containing:
  - Data loading and preprocessing  
  - Model definition and training loop  
  - Ray sampling and volume rendering logic  
  - Visualizations of rendered outputs and loss curves  

---

## 🎯 Why This Project?

This project demonstrates:

- **Mathematical rigor**: From positional encoding to volumetric rendering equations.  
- **Engineering practicality**: Integration of deep learning models with 3D vision data.  
- **Research curiosity**: Builds upon seminal NeRF work and opens possibilities for robotics, AR/VR, and simulation.  

Whether you're an engineer, scientist, or recruiter, this project reflects a strong foundation in **ML engineering**, **computer vision**, and **autonomous systems**.

---

## ▶️ Running the Code

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/NeRF_Blender_Project.git
cd NeRF_Blender_Project

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook NERF_Blender.ipynb

# 4. Follow the instructions in each cell to train and test the model
