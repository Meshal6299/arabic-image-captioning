# Arabic Image Captioning Project

## 🎯 Project Goal

The primary goal of this project is to develop and fine-tune a system that takes an image as input and generates a coherent, multi-sentence narrative description in the **Arabic language**. The target output is a descriptive paragraph of at least three cohesive sentences.

## 🛠️ Proposed Approach

Our approach is to adapt a state-of-the-art, pre-trained Vision-Language Model (VLM), such as **BLIP** or **GIT**. The core tasks will be:

1.  **Dataset Creation:** We will create a custom dataset by translating a subset of an existing English benchmark (like Flickr8k or MS COCO) into Arabic.
2.  **Model Fine-Tuning:** We will fine-tune the selected VLM on our new Arabic dataset to teach it to map image embeddings to fluent, multi-sentence Arabic text.
3.  **Evaluation:** We will test the model's ability to generate descriptive Arabic paragraphs and evaluate its performance.
4. **Input/Output:** The final system will accept a static image as **input** and produce a multi-sentence Arabic description as **output**.

## 📁 Repository Structure

```
├──  .venv/
├──  notebooks/
│   ├── 1_model_finetuning.ipynb      # Notebook for training the model
│   └── 2_model_evaluation.ipynb    # Notebook for testing and generating results
├── datasets/
│   ├── images/                     # (Source images)
│   └── captions_ar.txt            # Our translated Arabic captions
├── src/
│   └── (Any helper .py scripts)
└── README.md                       
```

## 📚 Key Resources

* Li, J., et al. (2022). **BLIP: Bootstrapping Language-Image Pre-training**
* Wang, J., et al. (2022). **GIT: A Generative Image-to-text Transformer for Vision and Language**
* Vinyals, O., et al. (2015). **Show and Tell: A Neural Image Caption Generator**
* Xu, K., et al. (2015). **Show, attend and tell: Neural image caption generation with visual attention**