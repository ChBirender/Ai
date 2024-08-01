# Ai

Install Jupyter Notebook in Python:

Windows:  
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

in requirements.txt

2. open cmd  
python -m pip install -r requirements.txt



3. create jy.bat file in user directory with below text:  
cd /d d:\Ai & jupyter notebook  
Here d:\Ai is location of notebook files.

4. run  
.\jy

Linux(ubuntu):  
sudo apt install python3 jupyter jupyter-notebook python3-notebook python3-pandas python3-matplotlib python3-lxml python3-numpy python3-seaborn python3-networkx python3-pil python3-sklearn jupyter-server python3-opencv
