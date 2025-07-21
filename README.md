
# 🧱 Concrete Crack Detection and Segmentation

This project uses a deep learning model to detect and segment cracks in concrete surfaces from images. It helps automate structural inspections by identifying and highlighting crack regions, aiding in early detection and maintenance of civil infrastructure.

---

## 📌 Features

- 🔍 Crack detection using a pretrained neural network
- 🖼️ Image-based segmentation of cracked regions
- 💡 Useful for structural health monitoring and assessment
- 💻 Easy to integrate into inspection pipelines

---

## 🧠 Model Overview

The model takes input images of concrete surfaces and outputs segmentation masks that highlight crack regions. It uses a U-Net architecture trained on a dataset of crack images.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/deathblare10/Wall_Crack_Detection.git
cd Wall_Crack_Detection
```

### 2. Set Up Environment

Create a virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Download the Pretrained Model

Make sure `pretrained_net_G.pth` is placed in the appropriate folder (e.g., `./models/`).

> ⚠️ If the model is not included, please download it from the [GitHub release](https://github.com/deathblare10/Wall_Crack_Detection/releases) or contact the maintainer.

### 4. Run Inference

```bash
python main.py --input_path ./sample_images/ --output_path ./results/
```

---

## 🖼️ Sample Results

| Input Image | Segmented Output |
|-------------|------------------|
| ![input](assets/sample_input.jpg) | ![output](assets/sample_output.jpg) |

---

## 📁 Project Structure

```
.
├── Analyszer/
│   ├── main.py
│   ├── utils.py
├── models/
│   └── pretrained_net_G.pth
├── sample_images/
├── results/
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib

---

## 🧑‍💻 Author

**Sanjay Deshmukh**  
[GitHub Profile](https://github.com/deathblare10)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
