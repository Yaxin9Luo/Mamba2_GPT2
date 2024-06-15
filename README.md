# Mamba2_GPT2
Implementation of codes to integrate mamba2 with gpt2. This is just a coding project for self-interests and practice, and there is nothing sota at all.

## Setup Environment 
### Conda
```bash 
git clone git@github.com:hu-po/karpamambathy
conda create -y --name karpamambathy python=3.11
conda activate karpamambathy
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install tiktoken==0.7.0
pip install datasets==2.20.0
cd karpamambathy
git clone https://github.com/state-spaces/mamba.git
pip install packaging==24.1
pip install causal-conv1d>=1.2.0
cd mamba && pip install -e . && cd ..
pip install wandb==0.17.1
```

### Docker

