# Ai

Install Jupyter Notebook in Python:

## Windows:  
1. create requirements.text file  
add below text:  

jupyter  
lxml  
matplotlib  
pandas  
Pillow  
scikit-learn  
numpy  
seaborn  
tensorflow  
jupyterlab  
notebook  
networkx  
torch  

in requirements.txt

2. open cmd  
python -m pip install -r requirements.txt



3. create jy.bat file in user directory with below text:  
cd /d d:\Ai & jupyter notebook  
Here d:\Ai is location of notebook files.

4. run  
.\jy

## Linux(ubuntu):  
sudo apt  install python3-full python3-virtualenv  
using virtual name as PyVenv  
virtualenv PyVenv  
source PyVenv/bin/activate  
python3 -m pip install tensorflow[and-cuda]  
python -m pip install -r requirements.txt  

edit ~/.bashrc  
add  
source PyVenv/bin/activate  
in last of it

source ~/.bashrc
