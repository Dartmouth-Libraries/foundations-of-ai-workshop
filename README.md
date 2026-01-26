# 🧠 Foundations of AI Workshop

Interactive Jupyter notebooks exploring AI concepts through hands-on visualizations. Designed for participants from all backgrounds and technical levels.

**Developed by:** Mashrekur Rahman  
**Institution:** Dartmouth Libraries

---

## 📚 Workshop Overview

This workshop series introduces fundamental AI concepts through interactive, visually-rich Jupyter notebooks. No prior machine learning experience required!

### Workshop 1: Foundations of AI — NLP to LLMs
*Understanding how AI learns language*

| Notebook | Topic | Description |
|----------|-------|-------------|
| `1_AI_learning.ipynb` | AI Learning | How AI models learn from data through parameter adjustment |
| `2_AI_modeling.ipynb` | AI Training Loop | The complete training cycle: input → prediction → loss → update |
| `3_encodings_embeddings.ipynb` | Text Representation | How text becomes numbers AI can understand |
| `4_attention.ipynb` | Attention Mechanism | The breakthrough behind modern transformers |
| `5_LLM_modeling.ipynb` | LLM Pipeline | Building large language models from data to deployment |

### Workshop 2: Foundations of AI — Deep Learning & Computer Vision
*Understanding how AI sees and creates*

| Notebook | Topic | Description |
|----------|-------|-------------|
| `6_Neurons_to_Networks.ipynb` | Neural Networks | From biological neurons to artificial neural networks |
| `7_how_AI_sees.ipynb` | CNNs & Vision | How convolutional neural networks process images |
| `8_how_AI_captures_time.ipynb` | LSTMs & Memory | How AI remembers sequences with LSTM networks |
| `9_how_AI_generates_images.ipynb` | Diffusion Models | How AI creates images from text prompts |

---

## 🚀 Getting Started

### Option 1: Dartmouth JupyterHub (Recommended for Dartmouth Users)

#### Prerequisites
- Dartmouth NetID and credentials
- Access to JupyterHub
- **Recommended Browser:** Chrome or Firefox (Safari has known compatibility issues with Plotly rendering)

#### Setup Instructions

1. Navigate to [Dartmouth JupyterHub](https://jhub.dartmouth.edu)
2. Log in with your Dartmouth credentials
3. Select **RR-workshops** environment and click **Start**
4. Open a **Terminal** (New → Terminal)
5. Run the following commands:

```bash
# Create workshop directory
mkdir -p ~/foundations-of-ai-workshop
cd ~/foundations-of-ai-workshop

# Clone the repository
git clone https://github.com/dartmouth-libraries/foundations-of-ai-workshop.git .

# Install dependencies
pip install -r requirements.txt
```

6. Open `0_setup.ipynb` and run it to verify all dependencies are installed
7. Start with the workshop notebooks!

### Option 2: Local Installation

#### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

#### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/dartmouth-libraries/foundations-of-ai-workshop.git
cd foundations-of-ai-workshop

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## 📦 Dependencies

The workshops require the following Python packages:

| Package | Purpose |
|---------|---------|
| `jupyter` | Notebook environment |
| `ipywidgets` | Interactive widgets |
| `matplotlib` | Static visualizations |
| `plotly` | Interactive 3D visualizations |
| `seaborn` | Statistical visualizations |
| `numpy` | Numerical computing |
| `scipy` | Scientific computing |
| `scikit-learn` | Machine learning utilities |
| `Pillow` | Image processing |
| `torch` | Deep learning (optional demos) |

Install all dependencies with:
```bash
pip install -r requirements.txt
```

---

## 🎯 Workshop Tips

### For Participants
- **Run cells in order** — Each notebook builds on previous cells
- **Interact with visualizations** — Drag sliders, click buttons, explore!
- **Don't worry about the code** — Focus on the concepts and visualizations
- **Ask questions** — The notebooks are guides, not tests

### For Instructors
- Each notebook is designed for ~10-15 minutes of guided exploration
- Interactive elements are designed for "wow moments" during demos
- Visualizations work best on Chrome/Firefox
- Pre-run notebooks before the workshop to cache any downloads

---

## 🔧 Troubleshooting

### Visualizations not rendering?
- Try Chrome or Firefox (Safari has known issues)
- Restart the kernel and run all cells
- Ensure `ipywidgets` is properly installed

### Import errors?
- Run `0_setup.ipynb` to check and install missing packages
- Restart the kernel after installing new packages

### Plots appear blank?
- Some Plotly visualizations require a moment to load
- Try scrolling or clicking on the plot area
- Check that JavaScript is enabled in your browser

---

## 📄 License

This project uses dual licensing:

- **Code** (Python scripts, configuration files): [MIT License](https://opensource.org/licenses/MIT)
- **Educational Materials** (notebooks, documentation, visualizations): [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (Creative Commons Attribution-NonCommercial 4.0 International)

You are free to use and adapt these materials for **non-commercial educational purposes** with appropriate attribution to Mashrekur Rahman and Dartmouth Libraries.

---

## 🙏 Acknowledgments

These materials were developed by Mashrekur Rahman for the Dartmouth Libraries' AI workshop series. Special thanks to all participants and contributors who provided feedback to improve these educational resources.
