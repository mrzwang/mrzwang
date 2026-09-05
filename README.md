<div align="center">
  
# Hi!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-wang-4ab10923a)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:wangrzm@mit.edu)

</div>

I'm a junior at MIT double majoring in Computer Science and Engineering (6-3) and Mathematics (18). I'm interested in machine learning systems, efficient computing, and the intersection of algorithms, software, and hardware.

---

## Featured Work

### Modeling the Taalas HC1 Inference Architecture

**Description:** Developed a reproducible architectural model of Taalas' HC1 LLM inference accelerator, investigating its custom MaskROM and Digital Oscillating Glitch RAM (DOGRAM) memory architectures. Characterized DOGRAM through transistor-level Cadence simulations at TSMC 65 nm and modeled scaling to advanced process nodes, then integrated custom hardware components into AccelForge to evaluate energy, latency, and throughput across transformer and CNN workloads. Performed a 5-workload × 4-ablation study to isolate the contributions of MaskROM and DOGRAM across memory- and compute-bound inference regimes.

---

### RL Adversarial LLM: Reinforcement Learning for LLM Code Generation
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/rl-adversarial-llm)
![ICLR](https://img.shields.io/badge/ICLR-2026%20Workshop-8A2BE2?style=flat)

**Description:** Developed an adversarial reinforcement learning framework for improving LLM code generation, implementing PPO and GRPO to fine-tune sub-4B parameter models through competitive self-play. Evaluated the approach on code-generation benchmarks, achieving a 15.9% improvement on HumanEval. This work was accepted to the ICLR 2026 Workshop on RSI.

**Links:** [GitHub](https://github.com/mrzwang/rl-adversarial-llm)

---

### In-Context Learning for Esoteric Programming Languages
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/In-Context-Learning-for-Esoteric-Programming-Languages)
![NeurIPS](https://img.shields.io/badge/NeurIPS-2025%20Workshops-8A2BE2?style=flat)

**Description:** Developed an in-context evaluation framework for extending LLM code generation to esoteric programming languages without additional fine-tuning. Built a benchmark and modular evaluation pipeline to compare prompting strategies and investigate model performance in low-resource programming environments. This work was accepted to the NeurIPS 2025 DL4C and LLM Evaluations Workshops.

**Links:** [GitHub](https://github.com/mrzwang/In-Context-Learning-for-Esoteric-Programming-Languages), [Supplementary Material](https://github.com/mrzwang/LLM-potential_reward_hacking_examples)

---

### NGFuzz: Neural-Guided Adversarial Fuzzing Framework
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/ngfuzz)

**Description:** Developed a neural-guided fuzzing framework that combines AFL with learned input mutation strategies for software vulnerability discovery. Implemented gradient-based adversarial input generation and continuous model retraining to guide exploration toward rare program paths, improving code coverage over traditional fuzzing baselines.

**Links:** [GitHub](https://github.com/mrzwang/ngfuzz)

---


## Other Notable Projects

<details open>
<summary><b>Research & ML Projects (Click to expand)</b></summary>

<br>

### FormattingSFT: Code Format Training Dataset Generator for LLM Fine-Tuning
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/FormattingSFT)

Specialized pipeline for creating supervised fine-tuning (SFT) datasets from Python code snippets to train language models on consistent output formatting. Implements AST-based docstring detection, tokenization-aware comment handling, and memory-efficient batch processing with PyArrow.

---

### PyTorch Transformer GPT From Scratch
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/PytorchTransformerGPT)

Implemented a GPT-style transformer language model in PyTorch through basic tensor operations. Features character-level transformer with manually implemented attention mechanisms, positional embeddings, and feed-forward networks. Trained on the OpenWebText dataset with efficient memory-mapped file handling.

---

### Neural Network Adversarial Patches
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/Neural-Network-Adversarial-Patches)

Explores the vulnerability of convolutional image classifiers to adversarial perturbations. Implements both brute-force and optimization-based methods for generating adversarial examples on MNIST, including a learned additive noise layer using Keras' functional API.

---

### Computer Use Agentic AI

Developed an autonomous browser interaction agent using AutoGen and Azure's Computer Use API. Built screenshot-based perception and action loops supporting browser navigation, custom model integration, safety checks, and human-in-the-loop approval for supervised web task automation.

</details>

<details open>
<summary><b>Competition & Applied Projects (Click to expand)</b></summary>

<br>

### UCOPC 2024: Optimal Team Selection for USA Gymnastics at Paris  
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/mrzwang/UCOPC2024)
[![UCSAS](https://img.shields.io/badge/UCSAS-2024%20Challenge-blue)](https://statds.org/events/ucsas2024/challenge.html)

Finalist in the Undergraduate division of the 2024 UCSAS Statistical Data Science Challenge, with poster featured at UCSAS 2024. Analyzed 26,000+ data entries from historic gymnastic results and implemented a dual-method framework combining linear assignment modeling with statistical inference (t-tests, Type II error analysis) for optimal five-member team selection ahead of Paris 2024.

---

### Object Detection Transformer Model with Web Integration
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/dthxe/obj-detection-transformer)

Browser-accessible object detection system leveraging a transformer model for zero-shot, text-prompt-based object detection. Built an interactive Flask application supporting image uploads and live webcam capture, with performance optimizations including model caching for reduced inference latency.

</details>

---

## Technical Skills

### Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Julia](https://img.shields.io/badge/-Julia-9558B2?style=flat&logo=julia&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-41454A?style=flat)

### ML & Scientific Computing
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

### Systems & Development
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

### Hardware & Architecture
![FPGA](https://img.shields.io/badge/-FPGA-555555?style=flat)
![AccelForge](https://img.shields.io/badge/-AccelForge-555555?style=flat)

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-wang-4ab10923a)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wangrzm@mit.edu)

</div>
