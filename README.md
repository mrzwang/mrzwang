# Hi!

I am a sophomore at MIT majoring in the intersection of Mathematics, Computer Science, and Artificial Intelligence, with a particular interest in Machine Learning.

## Current Research/Projects

### Computer Use Agentic AI
**Description:** Developing an autonomous browser interaction system using both AutoGen framework and Azure's Computer Use Preview API. This project enables AI models to navigate web interfaces through a sophisticated action handling system supporting clicks, typing, scrolling, and keyboard shortcuts. The implementation features custom Hugging Face model integration with function-calling capabilities, safety checks for user approval, screenshot-based visual feedback loops, and automatic tab management. The system maintains context awareness through URL tracking and provides detailed reasoning summaries, creating a human-in-the-loop experience where AI can perform web tasks while allowing human supervision. The architecture supports both streaming and synchronous completions with configurable model parameters, providing a foundation for research into autonomous web navigation capabilities.  
**Note:** This is proprietary work in progress; source code is not publicly available at this time.

### RL Adversarial LLM: Reinforcement Learning Framework for LLM Code Generation 
**Description:** Developed an advanced reinforcement learning framework for enhancing language model capabilities, implementing both PPO (Proximal Policy Optimization) and GRPO (General Reinforcement Policy Optimization) algorithms. The system focuses on RL fine-tuning sub-4B parameter models to improve code generation quality, consistency, and complexity. A core feature is the adversarial training framework, where two language models compete against each other in real-time, continuously improving through reinforcement learning feedback loops. This creates a self-improving ecosystem where models learn to generate increasingly sophisticated code by attempting to outperform their opponents.  
**Links:** [GitHub](https://github.com/mrzwang/rl-adversarial-llm)

## Research

### NGFuzz: Neural-Guided Adversarial Fuzzing Framework  
**Description:** Combines traditional AFL fuzzing with neural network guidance to intelligently direct input mutations for enhanced software vulnerability discovery. Implements gradient-based optimization and adversarial input generation to systematically explore rare and complex program paths. Features continuous model retraining for adaptive fuzzing that evolves with program behavior, significantly improving code coverage and bug detection efficiency.  
**Links:** [GitHub](https://github.com/mrzwang/ngfuzz)

### In-Context Learning for Esoteric Programming Languages  
**Description:** Developed a zero-shot, in-context evaluation framework that extends LLM reasoning to esoteric languages without any additional fine-tuning. Built a modular pipeline to compare full versus minimal context prompting and introduced a lightweight in-context reinforcement method that delivered measurable improvements on custom “EsoEval” benchmarks over standard HumanEval.  
**Links:** [GitHub](https://github.com/mrzwang/In-Context-Learning-for-Esoteric-Programming-Languages), [Supplementary Material](https://github.com/mrzwang/LLM-potential_reward_hacking_examples) 

### FormattingSFT: Code Format Training Dataset Generator for LLM Fine-Tuning
**Description:** Developed a specialized pipeline for creating supervised fine-tuning (SFT) datasets from Python code snippets to train language models on consistent output formatting. Implements AST-based docstring detection and tokenization-aware comment handling to preserve code structure while removing non-essential elements. Features intelligent regex-based code sanitization to filter potentially harmful patterns and memory-efficient batch processing with PyArrow for handling large datasets. The system generates structured prompt-completion pairs with deterministic output formatting, serving as a first-stage training step before reinforcement fine-tuning (RFT) to establish formatting patterns for code blocks, predictions, and structured responses.
**Links:** [GitHub](https://github.com/mrzwang/FormattingSFT)

## Projects
### PyTorch Transformer GPT From Scratch
**Description:** Implemented a GPT-style transformer language model completely from scratch using only PyTorch's basic building blocks. The project features a character-level transformer with manually implemented attention mechanisms, positional embeddings, and feed-forward networks without relying on high-level transformer modules. Includes both a full transformer architecture and a simpler bigram language model. The implementation uses concepts like causal masking, multi-head attention, residual connections, and autoregressive generation with numerical stability techniques. The project also features efficient data handling with memory-mapped files and random chunk sampling for training on the OpenWebText dataset.  
**Links:** [GitHub](https://github.com/mrzwang/PytorchTransformerGPT)

### Neural Network Adversarial Patches
**Description:** Explores the vulnerability of convolutional image classifiers to adversarial perturbations. Implements both brute-force and optimization-based methods for generating adversarial examples on MNIST, including a learned additive noise layer using Keras' functional API.  
**Links:** [GitHub](https://github.com/mrzwang/Neural-Network-Adversarial-Patches)

### UCOPC 2024: Optimal Team Selection for USA Gymnastics at Paris  
**Description:** Finalist project in the Undergraduate division of the 2024 UCSAS Statistical Data Science Challenge, with poster featured at UCSAS 2024. The project sifts and works with over 26000 data entires from historic gymnastic results and implements a dual-method framework for selecting optimal five-member teams for the USA Men’s and Women’s Artistic Gymnastics programs ahead of Paris 2024. The first method applies linear assignment modeling to optimize event-specific lineups based on individual expected scores; the second leverages statistical inference (including t-tests and Type II error analysis) to identify high-impact all-arounders capable of minimizing medal upset risk. The pipeline integrates data cleaning, performance simulation, and ranking methodologies to balance specialization and team consistency under Olympic scoring constraints.
**Links:** [GitHub](https://github.com/mrzwang/UCOPC2024) | [UCSAS 2024 Challenge](https://statds.org/events/ucsas2024/challenge.html)  

### Object Detection Transformer Model with Web Integration
**Description:** Developed a browser-accessible object detection system leveraging a transformer model for zero-shot, text-prompt-based object detection. Built an interactive Flask application supporting both image uploads and live webcam capture, with a Pillow-based pipeline for preprocessing, bounding box annotation, and dynamic confidence filtering. The modular architecture enables rapid extension to new detection targets, UI components, and backend services, and integrates performance optimizations such as model caching for reduced inference latency. This also features the ability to be further finetuned to gain specific object classes.  
**Links:** [GitHub](https://github.com/dthxe/obj-detection-transformer)


