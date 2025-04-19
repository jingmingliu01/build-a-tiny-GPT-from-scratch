# 🧠 Build a Tiny GPT from Scratch

An educational, minimalist implementation of GPT-style language models in PyTorch, following [Andrej Karpathy’s video walkthrough](https://www.youtube.com/watch?v=kCc8FmEb1nY). This repo includes both a **Bigram Language Model** and a **Transformer-based GPT**, modularized for clarity and extensibility.

---

## 🔍 Overview

This project walks through building a GPT-style model from scratch, with the following components:

- 🧱 A **Bigram Language Model** for foundational understanding
- 🔁 A **Transformer-based GPT** with:
  - Tokenizer
  - Self-attention mechanism
  - LayerNorm & MLP
  - Training loop with cross-entropy loss
- 📚 Trained and evaluated on the Shakespeare dataset using Google Colab

Check out the [Colab notebooks](https://github.com/jingmingliu01/build-a-tiny-GPT-from-scratch) to run and experiment with the models.

---

## 📝 Companion Article

I also wrote a companion article (in both English and Chinese) exploring how different modeling approaches tackle the core challenges of language modeling:

📄 [**Language Model 01: From Bigram, N-gram to GPT** (PDF)](https://github.com/jingmingliu01/Intro-to-AI/blob/main/Articles/Language%20Model%2001_%20From%20Bigram%2C%20n-gram%20to%20GPT%20%E2%80%94%20How%20do%20they%20respond%20to%20the%20core%20issues%20of%20language%20modeling_%20---%20%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B01_%20%E4%BB%8EBigram%E3%80%81n-gram%E5%88%B0GPT%E2%80%94%E2%80%94%E5%AE%83%E4%BB%AC%E5%A6%82%E4%BD%95%E5%9B%9E%E5%BA%94%E8%AF%AD%E8%A8%80%E5%BB%BA%E6%A8%A1%E7%9A%84%E6%A0%B8%E5%BF%83%E9%97%AE%E9%A2%98%EF%BC%9F.pdf)

---

## 🚀 Getting Started

Run the notebooks directly on Google Colab:

- [`bigram_build_GPT_from_scratch.ipynb`](./bigram_build_GPT_from_scratch.ipynb)
- [`gpt_build_GPT_from_scratch.ipynb`](./gpt_build_GPT_from_scratch.ipynb)

Make sure to install PyTorch in your environment or use Colab for convenience.

---

## 🙏 Acknowledgement

This project closely follows [Andrej Karpathy's GPT tutorial](https://github.com/karpathy/ng-video-lecture). All credit for the original idea and inspiration goes to him. My goal here is to internalize and extend the knowledge through hands-on implementation and reflection.

---

## 📄 License

This project is released under the **MIT License**, with proper attribution to Andrej Karpathy as the source of the tutorial and base code structure. Please refer to his [original repo](https://github.com/karpathy/ng-video-lecture) if you intend to use this work commercially or academically.


