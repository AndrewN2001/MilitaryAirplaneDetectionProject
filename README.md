# Military Aircraft Detection with CNN

This project uses a Convolutional Neural Network (CNN) to detect military aircraft in images. The model is trained and evaluated on a dataset specifically created for aircraft detection, which contains labeled images of military aircraft and non-aircraft objects.
![image](https://github.com/user-attachments/assets/a69206ae-bc93-42bb-907c-efc554a0722f)

## Project Overview

The aim of this project is to build a CNN that can identify images of military aircraft. This project can be used for object detection in surveillance applications, where rapid and accurate aircraft recognition is essential.

## Getting Started

### Prerequisites

To run this project, you need:
- Python 3.7+
- TensorFlow or PyTorch (your choice of deep learning framework)
- Additional libraries: `numpy`, `pandas`, `matplotlib`, `opencv-python`, `sklearn`

Install these dependencies using:

```bash
pip install -r requirements.txt

```

Data Preparation
Extract the Dataset: Download and extract archive.zip in the data/ directory:

Download from here: https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset

```bash
unzip archive.zip -d MilitaryAirplaneDetectionProject/
```

Dataset Structure: Ensure the data follows this structure:

```bash
MilitaryAirplaneDetectionProject/
├── archive/
│   ├── annotated_samples/
│   └── crop/
│   └── dataset/
```
