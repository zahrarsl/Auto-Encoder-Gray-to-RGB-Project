```markdown
# 🎨 Auto-Encoder Gray to RGB Conversion Project

This project implements an **Auto-Encoder** model designed to convert grayscale images into their corresponding **RGB color versions** using deep learning techniques.

## 📖 Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Introduction

Image colorization is the process of transforming grayscale images into colorful images. In this project, an **Auto-Encoder** architecture is utilized to automate the colorization of grayscale images, generating realistic RGB outputs.

## ⚙️ Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/autoencoder-gray2rgb.git
    cd autoencoder-gray2rgb
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

To train the model on grayscale images and generate their RGB counterparts, run:

```bash
python train.py --dataset /path/to/grayscale/dataset --epochs 100
```

After training, the colorized images will be saved in the outputs/ directory.

📊 Results
Here’s a comparison of the grayscale and colorized images:

Grayscale Image:


Colorized Image:


💡 Contributing
Feel free to contribute by opening issues or submitting pull requests.
