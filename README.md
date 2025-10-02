# Foundations of AI Workshop: Interactive Visualizations

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dartmouth-libraries/foundations-of-ai-workshop/main)

Welcome to the Foundations of AI Workshop! This repository contains interactive Jupyter notebooks designed to help you understand core concepts in artificial intelligence and machine learning through hands-on visualizations.

## 🎯 Workshop Overview

This workshop demystifies artificial intelligence by providing interactive, visual explanations of how AI systems learn, process information, and generate outputs. No prior programming experience required to explore the visualizations!

## 📚 Notebooks

### 1. AI Learning (`1_AI_learning.ipynb`)
**What it teaches:** How AI models learn from data through trial and error

**Key concepts:**
- Understanding parameters and how they're adjusted
- Visualizing the learning process in real-time
- Experimenting with different parameter values
- Seeing how AI finds patterns through iteration

**Interactive elements:**
- Adjustable weight sliders (W₁, W₂, W₃)
- Non-linearity power controls (P₁, P₂, P₃)
- Feature interaction mixer
- Real-time error calculation
- Accuracy visualization bar
- 3D training data cloud
- Live predictions vs. reality comparison

**What you'll do:** Manipulate parameters and watch the AI model improve its predictions, gaining intuition for how machine learning optimization works.

---

### 2. AI Training Loop (`2_AI_modeling.ipynb`)
**What it teaches:** The complete cycle of how AI systems are trained

**Key concepts:**
- Input data → Model → Output → Comparison → Learning → Repeat
- Understanding forward and backward propagation
- Role of loss functions in measuring error
- How optimizers update model weights
- The relationship between all components

**Interactive elements:**
- Step-by-step navigation through the training cycle
- Visual highlighting of active components
- Detailed explanations for each stage:
  - Input Data: Training examples
  - AI Model: Neural network architecture
  - Predictions: Model outputs (ŷ)
  - True Values: Correct answers (y)
  - Loss Function: Error measurement
  - Optimizer: Weight updates
- Progress tracking through training iterations

**What you'll do:** Navigate through the six stages of AI training, understanding how each component contributes to the learning process.

---

### 3. Encodings vs Embeddings (`3_encodings_embeddings.ipynb`)
**What it teaches:** How computers convert words into numbers and why some methods are smarter than others

**Key concepts:**
- Traditional encodings: Simple but limited (one-hot encoding)
- Embeddings: Capturing meaning and relationships
- Semantic similarity in vector space
- How word relationships emerge from data

**Interactive elements:**
- Vector space visualizations (2D and 3D)
- Word positioning based on meaning
- Similarity comparisons between words
- Live demonstration with sentence embeddings
- Next-word prediction using embeddings
- Comparison of encoding methods

**Example demonstration:**
- Shows how the model predicts "sat" for "The rabbit" despite never seeing rabbits in training
- Illustrates semantic understanding through vector similarity

**What you'll do:** See how words are represented as points in space, where similar meanings cluster together, enabling AI to understand language context.

---

### 4. Attention Mechanism (`4_attention.ipynb`)
**What it teaches:** How modern AI focuses on relevant information (the breakthrough behind ChatGPT)

**Key concepts:**
- Attention as selective focus
- Multi-head attention (different perspectives)
- Attention weights and their meaning
- How transformers process sequences

**Interactive elements:**
- 3D visualization of word relationships
- Attention flow connections between words
- Color-coded attention heads:
  - **Red (Local):** Focuses on nearby words
  - **Teal (Semantic):** Content-based relationships
  - **Blue (Long-range):** Distant dependencies
  - **Green (Mixed):** Combined patterns
- Interactive text processing
- Weight visualization showing strength of connections
- Opacity indicating attention intensity

**Example text analyzed:**
"Natural language processing enables machines to understand human language. Transformers use attention mechanisms to identify word relationships. These models process context dependencies efficiently."

**What you'll do:** Watch how AI "pays attention" to different words when understanding a sentence, seeing which words relate to each other through 3D connection visualizations.

---

### 5. LLM Development Pipeline (`5_LLM_modeling.ipynb`)
**What it teaches:** The complete journey of building a Large Language Model (like ChatGPT)

**Key concepts:**
- The five stages of LLM development
- Scale of modern AI systems (data, compute, cost)
- Alignment and safety considerations
- From raw data to deployed model

**Interactive elements:**
- Step-by-step pipeline navigation (14 detailed steps)
- Stage-by-stage visual highlighting
- Comprehensive descriptions for each phase

**The 14 Steps:**

**Stage 1: Data Collection & Processing**
1. Web Crawling (Common Crawl - billions of pages)
2. Books & Articles (quality knowledge sources)
3. Code Repositories (GitHub, programming patterns)
4. Data Cleaning & Deduplication (removing 30-40% duplicates)
5. Quality Filtering & Safety (PII removal, bias reduction)
6. Tokenization (converting text to numbers)

**Stage 2: Pre-training**
7. Transformer Architecture (attention + feed-forward networks)
8. Pre-training Process (next token prediction on 1000+ GPUs, 3-6 months)

**Stage 3: Alignment & Fine-tuning**
9. Supervised Fine-Tuning (~100K instruction examples)
10. Human Feedback Collection (rating and ranking)
11. RLHF Training (PPO, DPO, Constitutional AI)

**Stage 4: Evaluation & Safety**
12. Comprehensive Testing (MMLU, HellaSwag, safety benchmarks)

**Stage 5: Deployment & Monitoring**
13. Model Deployment (optimization, API, scaling)
14. Continuous Monitoring (usage patterns, improvements)

**What you'll do:** Navigate through the entire LLM development process, understanding the massive effort, resources, and careful considerations that go into creating AI systems like ChatGPT.

---

## 🚀 Getting Started

### Option 1: Run Online (Easiest - No Installation)

Click the Binder badge at the top of this README to launch an interactive environment in your browser. Note: It may take 1-2 minutes to load.

### Option 2: Run Locally

1. **Prerequisites:**
   ```bash
   Python 3.8+
   pip or conda