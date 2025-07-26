# GPU vs CPU Acceleration Project

This project investigates the performance differences between **GPU** and **CPU** acceleration across multiple deep learning models using distributed training techniques. It includes a set of Jupyter notebooks, training logs, performance plots, and configuration files for five distinct projects with varying models and hardware settings.

---

## 📁 Repository Structure

```

notebooks/
├── project 1/
│   ├── project1\_1gpu.ipynb
│   ├── VGG16\_3epochs\_1GPU.json
│   └── ...
├── project 2/
│   ├── project1\_1GPU.ipynb
│   ├── LeNet\_10epochs\_1GPU.json
│   └── ...
├── project 3/
│   ├── project3\_plots.ipynb
│   ├── plots/
│   │   ├── confusion\_matrix\_1gpu.png
│   │   └── ...
│   └── project3\_1gpu.json
├── project 4/
│   ├── project4.ipynb
│   ├── project4-2gpus.json
│   └── ...
├── project 5/
│   ├── Project5\_1gpu.ipynb
│   └── RNN\_10epochs\_2GPU.json

````

---

## 🎯 Objectives

- Compare model training time and performance between CPU and GPU.
- Evaluate scalability with multi-GPU setups.
- Generate plots to visualize speedup, throughput, accuracy, and training time.

---

## 🧪 Projects Overview

| Project | Model      | Epochs | Hardware Configurations |
|---------|------------|--------|--------------------------|
| 1       | VGG16      | 3      | 1 GPU                    |
| 2       | LeNet      | 10     | 1 GPU, 2 GPUs            |
| 3       | Custom CNN | 10     | CPU, 1 GPU, 2 GPUs       |
| 4       | RNN        | Varies | CPU, 1 GPU, 2 GPUs       |
| 5       | RNN        | 10     | 1 GPU, 2 GPUs            |

---

## 🖥️ Technologies

- Python
- TensorFlow / Keras / PyTorch (depending on notebook)
- Jupyter Notebooks
- NVIDIA CUDA
- Matplotlib / Seaborn
- Git

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/HafssaBN/GPU-vs-CPU-acceleration-project.git
cd GPU-vs-CPU-acceleration-project
````

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
```

3. **Install dependencies**

You can install packages based on what’s used in the notebooks:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` doesn’t exist, open each notebook to install specific packages like:
> `tensorflow`, `torch`, `matplotlib`, `numpy`, `seaborn`, etc.

---

## 🚀 Usage

1. Launch Jupyter:

```bash
jupyter notebook
```

2. Navigate to the `notebooks/project X` folders to open and run each project.

3. Use plots to analyze:

* Speedup comparisons
* Training time
* Accuracy/loss over epochs
* Throughput

---

## 📊 Sample Output

Example plot from Project 3:

* **Training Time Comparison**

![training\_time](notebooks/project%203/plots/training_time_comparison.png)

---

## 📌 Notes

* The line endings warning (CRLF/LF) is expected on Windows. It doesn't affect execution.
* GPU performance depends on the environment setup (CUDA, cuDNN, etc.).
* Ensure GPU drivers and software are correctly installed to run GPU notebooks.

---

## 🧑‍💻 Author

**Hafssa B.**

* GitHub: [@HafssaBN](https://github.com/HafssaBN)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

```

---

Let me know if you want this tailored for a specific framework (like only TensorFlow or PyTorch), or if you'd like help generating a `requirements.txt` or `.gitignore`!
```
