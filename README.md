# Mamba2_GPT2
Implementation of codes to integrate mamba2 with gpt2. This is just a coding project for self-interests and practice, and there is nothing sota at all.

## Setup Environment 
### Conda
```bash 
git clone https://github.com/Yaxin9Luo/Mamba2_GPT2.git
conda create -y --name mamba_gpt python=3.11
conda activate mamba_gpt
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install tiktoken==0.7.0
pip install datasets==2.20.0
cd mamba_gpt
git clone https://github.com/state-spaces/mamba.git
pip install packaging==24.1
pip install causal-conv1d>=1.2.0
cd mamba && pip install -e . && cd ..
pip install wandb==0.17.1
```

### Docker

