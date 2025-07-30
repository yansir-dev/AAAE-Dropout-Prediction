# Attention-Augmented Autoencoder for Robust Student Dropout Prediction

This repository contains the implementation and resources for the paper "Attention-Augmented Autoencoder for Robust Student Dropout Prediction".

## 🌟 Overview

This project presents a novel approach to student dropout prediction using an attention-augmented autoencoder architecture. The model combines the power of autoencoders for feature learning with attention mechanisms to focus on the most relevant student characteristics for dropout prediction.

**Keywords**: Student Dropout Prediction, Attention Mechanism, Autoencoder, Educational Data Mining, Deep Learning

---

## 🏛️ Repository Structure

```
AAAE-Dropout-Prediction/
│
├── LICENSE              # 📜 开源许可证 (MIT License)
├── README.md            # 🚀 仓库主页 (You are here!)
├── requirements.txt     # 📦 Python 依赖包
├── .gitignore           # 🙈 Git 忽略规则
│
├── Codebase/            # 💻 核心源代码 (Core Source Code)
│   └── Release.ipynb    #    - 包含模型定义、训练和评估全部流程的 Jupyter Notebook
│
├── Database/            # 💾 数据集 (Dataset)
│   ├── Processed/       #    - 存储预处理后 (如SMOTE、标准化) 的数据
│   └── RawData/         #    - 存放原始 .csv 数据集
│
└── Paper/               # 📄 论文与文档 (Paper & Documentation)
    ├── paper.pdf        #    - "Attention-Augmented Autoencoder" 研究论文
    └── Figure/          #    - 论文或报告中使用的图表
```

---

## 🚀 Getting Started

Follow these steps to set up the project and run the model.

### **1. Setup**

First, clone the repository and install the required dependencies.

Bash

```
# Clone the repository
git clone https://github.com/BreCaspian/AAAE-Dropout-Prediction.git
cd 

# Install dependencies (including Jupyter)
pip install -r requirements.txt
```

### **2. Data Preparation**

Place your raw student dataset (`.csv` file) inside the **`Database/RawData/`** directory. The Jupyter Notebook is configured to load data from this location.

### **3. Running the Model**

All code for data processing, model training, and evaluation is contained in a single Jupyter Notebook.

1. Launch Jupyter Lab or Jupyter Notebook from your terminal:

   Bash

   ```
   jupyter lab
   ```

2. In your browser, navigate to `Codebase/` and open **`Release.ipynb`**.

3. Execute the cells sequentially from top to bottom to reproduce the entire workflow and results.

------

## 📊 Model Architecture

> ⏳ *This section will be updated upon publication.*

## 📈 Results

> ⏳ *This section will be updated upon publication.*

---

## 📄 Citation

If you use this code or find our work helpful, please cite:

```bibtex
@article{paper_2024,
  title={Attention-Augmented Autoencoder for Robust Student Dropout Prediction},
  author={Name and Co-authors},
  journal={Journal Name},
  year={2025},
  volume={XX},
  pages={XXX-XXX}
}
```

## 📝 License

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.

## 🤝 Contact

For questions, feedback, or collaboration inquiries, please reach out to:  [yaoyuzhuo6@gmial.com]&[yansihan6636@gmail.com]
