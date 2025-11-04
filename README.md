# Arabic Image Captioning Project

## 🎯 Project Goal

The primary goal of this project is to develop and fine-tune a system that takes an image as input and generates a coherent, multi-sentence narrative description in the **Arabic language**. The target output is a descriptive paragraph of at least three cohesive sentences.

## 🛠️ Proposed Approach

Our approach is to adapt a state-of-the-art, pre-trained Vision-Language Model (VLM), such as **BLIP** or **GIT**. The core tasks will be:

1.  **Dataset Creation:** We will create a custom dataset by translating an existing English benchmark into Arabic.
2.  **Model Fine-Tuning:** We will fine-tune the selected VLM on our new Arabic dataset to teach it to map image embeddings to fluent, multi-sentence Arabic text.
3.  **Evaluation:** We will test the model's ability to generate descriptive Arabic paragraphs and evaluate its performance.
4. **Input/Output:** The final system will accept a static image as **input** and produce a multi-sentence Arabic description as **output**.

## 📁 Repository Structure

```
├── .venv/
├── data/
├── notebooks/
│   ├── images/
│   └── combined_descriptions.txt
├── src/
├── .gitignore
└── README.md                       
```

## 📚 Key Resources

* Li, J., et al. (2022). **BLIP: Bootstrapping Language-Image Pre-training**
* Wang, J., et al. (2022). **GIT: A Generative Image-to-text Transformer for Vision and Language**
* Vinyals, O., et al. (2015). **Show and Tell: A Neural Image Caption Generator**
* Xu, K., et al. (2015). **Show, attend and tell: Neural image caption generation with visual attention**

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Meshal6299/arabic-image-captioning.git

cd arabic-image-captioning
```

### 2️⃣ Create and Activate a Virtual Environment
```bash
python3 -m venv .venv

# 🪟 Windows
.venv\Scripts\activate
# 🐧 macOS / Linux
source .venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
