# 🧠 PCA on MNIST Dataset

This project demonstrates **Principal Component Analysis (PCA)** from scratch using **Singular Value Decomposition (SVD)** on the MNIST dataset of handwritten digits. It focuses on dimensionality reduction, reconstruction, and visualization.

---

## 📁 Project Structure

```
PCA_MNIST/
├── PCA.ipynb                # Main PCA implementation
├── PCA_Mathematically.ipynb# Conceptual explanation and derivation
├── data/
│   └── mnist_train.csv      # <--- Download and place this file here
├── LICENSE
└── README.md
```

---

## 📦 Dataset Requirement

Your code expects the **CSV version of MNIST** to be located at:

```
data/mnist_train.csv
```

This file **is not included in the repository** due to GitHub's file size restrictions.

---

### 📥 How to Download `mnist_train.csv`

You can download the dataset from **Kaggle**:

- 📎 [MNIST in CSV format on Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv)

After downloading:

1. Extract the ZIP file.
2. Place `mnist_train.csv` inside the `data/` folder in this repo.

```bash
PCA_MNIST/
└── data/
    └── mnist_train.csv  ✅  <-- put the file here
```

---

## 🛠 Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Saber0722/PCA_MNIST.git
   cd PCA_MNIST
   ```

3. **Install Dependencies**:

   ```bash
   pip install numpy pandas matplotlib
   ```

4. **Download the Dataset** (see above), then place it into `data/mnist_train.csv`.

---

## 🚀 How to Run

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open and execute the following notebooks:

- 📘 `PCA.ipynb`: Runs PCA on the dataset
- 📘 `PCA_Mathematically.ipynb`: Walks through the math and theory

---


## ⚠️ Troubleshooting

If you run into a `FileNotFoundError` like this:

```
FileNotFoundError: [Errno 2] No such file or directory: 'data/mnist_train.csv'
```

✅ It means you need to download the dataset and place it in the `data/` folder. Follow the [instructions above](#how-to-download-mnist_traincsv).

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) for more info.
