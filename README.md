# Ai

Install Jupyter Notebook in Python:

## Windows:  
1. python -m pip install torch fairseq tensorflow[and-cuda] torchvision torchaudio pathlib pydub librosa pandas tensorboardx jupyter lxml matplotlib pandas Pillow scikit-learn numpy seaborn jupyterlab notebook networkx


2. create jy.bat file in user directory with below text:  
cd /d d:\Ai & jupyter notebook  
Here d:\Ai is location of notebook files.

4. run  
.\jy

## Linux(ubuntu):  
cd ~  
sudo apt  install python3-full python3-virtualenv  
***using virtual name as PyVenv***  
virtualenv PyVenv  
source ~/PyVenv/bin/activate  
python -m pip install torch fairseq tensorflow[and-cuda] torchvision torchaudio pathlib pydub librosa pandas tensorboardx jupyter lxml matplotlib pandas Pillow scikit-learn numpy seaborn jupyterlab notebook networkx


edit ~/.bashrc  
add  
source ~/PyVenv/bin/activate  
in last of it

source ~/.bashrc
