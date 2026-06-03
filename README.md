# 3D-Aware Generative Modeling of Expressive Human Avatars with Multi-Part Control

<img style="max-width: 100%;" src="https://github.com/rizwanchouhan/gema/blob/main/resources/wax.png" alt="Proposed Framework Overview">

# 📌 Overview

This project presents a 3D-aware generative framework for expressive human avatar synthesis with structured multi-part control. The method focuses on learning a disentangled representation of human identity, expression, and semantic body regions, enabling fine-grained and controllable avatar generation.

# 🧠 Architecture

The proposed framework consists of three main components:

- Identity–Expression Disentanglement Module  
- Part-Aware Latent Decomposition Module  
- 3D Feature Field with Neural Rendering  

The overall pipeline learns a structured representation that is mapped to a continuous 3D feature field and rendered into a view-consistent human avatar.

# ⚙️ Requirements

Install the required libraries:

- Python 3.8+
- PyTorch
- OpenCV
- NumPy
- torchvision
- matplotlib

# Datasets

We evaluate our method on four widely used human-centric datasets for pose, motion, and in-the-wild human understanding tasks.

## Human3.6M
Human3.6M is a large-scale motion capture dataset with 3D human pose annotations captured in a controlled indoor environment. It includes daily activities performed by multiple subjects and is widely used for benchmarking 3D human pose estimation methods. Download the dataset from [here](https://vision.imar.ro/human3.6m/).

## DeepFashion
DeepFashion is a large-scale fashion dataset containing in-the-wild images with rich annotations, including clothing categories, landmarks, and retrieval pairs. It is commonly used for fashion recognition and image-based retrieval tasks. Download the dataset from [here](https://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html).

## 3DPW
3DPW is a challenging dataset that provides in-the-wild videos with accurate 3D human mesh annotations captured using IMU-based motion tracking. It enables evaluation of 3D human pose and mesh reconstruction in real-world settings. Download the dataset from [here](https://virtualhumans.mpi-inf.mpg.de/3DPW/).

## MPV
MPV is a multi-person dataset designed for analyzing human interactions and complex motion in real-world video sequences. It contains diverse scenarios with occlusions and multiple interacting subjects. Download the dataset from [here](https://mvp-dataset.github.io/).
