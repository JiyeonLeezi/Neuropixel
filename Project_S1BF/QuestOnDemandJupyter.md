## 1. Quest OnDemand - Quest GNOME Desktop
<img width="624" height="758" alt="image" src="https://github.com/user-attachments/assets/f38e468b-5f3a-41e3-bf13-6bfe98152c7f" />

### (1) mamba module load and setting environment

module purge all

module load mamba/24.3.0

mamba create -n bombcell python=3.11

conda activate bombcell

### (2) bombcell install

pip install uv

uv pip install bombcell

### (3) Kernel 

conda install ipykernel

python -m ipykernel install --user --name=bombcell --display-name "bombcell"

## 2. Jupyter
### (1) Open BombcellScript_sur_spikeGLX
### (2) Kernel name - bombcell
