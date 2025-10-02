# Foundations of AI Workshop

Interactive Jupyter notebooks exploring AI concepts through hands-on visualizations.

**Created by:** Mashrekur Rahman  
**Institution:** Dartmouth Libraries  
**License:** MIT

## Workshop Notebooks

1. **AI Learning** (`1_AI_learning.ipynb`) - How AI models learn from data through parameter adjustment
2. **AI Training Loop** (`2_AI_modeling.ipynb`) - The complete training cycle from input to learning
3. **Encodings vs Embeddings** (`3_encodings_embeddings.ipynb`) - How text is represented in AI systems
4. **Attention Mechanism** (`4_attention.ipynb`) - The breakthrough behind modern transformers
5. **LLM Development Pipeline** (`5_LLM_modeling.ipynb`) - Building large language models from scratch

## Getting Started (Dartmouth JupyterHub)

### Prerequisites
- Dartmouth NetID and credentials
- Access to JupyterHub

### Setup Instructions

1. Navigate to [Dartmouth JupyterHub](https://jhub.dartmouth.edu)
2. Log in with your Dartmouth credentials
3. Select **RR-workshops** environment and click **Start**
4. Open a **Terminal** (New → Terminal)
5. Run the following commands:

```bash
mkdir -p ~/foundations-of-ai-workshop
cd ~/foundations-of-ai-workshop
git clone https://github.com/dartmouth-libraries/foundations-of-ai-workshop.git .
pip install -r requirements.txt