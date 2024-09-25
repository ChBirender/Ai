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

# Cuda Cudnn Tensorrt

sudo dpkg -i cuda-repo-ubuntu2204-12-4-local_12.4.1-550.54.15-1_amd64.deb  
sudo cp /var/cuda-repo-ubuntu2204-12-4-local/cuda-*-keyring.gpg /usr/share/keyrings/  
sudo apt-get update  
sudo apt-get -y install cuda-toolkit-12-4  
sudo apt-get install -y cuda-drivers-550  
sudo apt-get install -y nvidia-driver-550-open  
sudo apt-get -y install cudnn9-cuda-12  
sudo dpkg -i cudnn-local-repo-ubuntu2204-9.1.0_1.0-1_amd64.deb  
sudo cp /var/cudnn-local-repo-ubuntu2204-9.1.0/cudnn-local-52C3CBCA-keyring.gpg /usr/share/keyrings/  
sudo apt-get update  
sudo apt-get -y install cudnn9-cuda-12  
sudo dpkg -i nv-tensorrt-local-repo-ubuntu2204-10.1.0-cuda-12.4_1.0-1_amd64.deb  
sudo cp /var/nv-tensorrt-local-repo-ubuntu2204-10.1.0-cuda-12.4/nv-tensorrt-local-E3A02F15-keyring.gpg /usr/share/keyrings/  
sudo apt-get update  
sudo apt install tensorrt tensorrt-dev tensorrt-libs python3-libnvinfer* libnvinfer*  
pip install keras typing_extensions==4.12.2 tensorflow-probability[tf]==0.23 tensorflow[and-cuda]==2.15.1  
pip install torch==2.4.1 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124  
