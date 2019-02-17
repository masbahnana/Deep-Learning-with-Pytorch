# Deep-Learning-with-Pytorch

Detailed installation steps (software-wise)

The steps should be listed in a way that it prepares the system environment to be able to test the codes.

## Anaconda Python:
    Download Anaconda Python version 3,6 from the Anaconda
    Run the Download file from the command line by typing:
      'cd ~/Downloads/'
      './Anaconda3-5.0.1-Linux-x86_64.sh'
    You will be prompted to say yes. Following all the instructions would lead to an installed anaconda Python.
    Open a new terminal and check the default python points to 3.6.4

## CUDA 9:
    Download CUDA 9 toolkit from NVIDIA
    Select Linux, x86_64
      'sudo dpkg -i cuda-repo-ubuntu1704-9-0-local_9.0.176-1_amd64.deb'
      'sudo apt-key add /var/cuda-repo-<version>/7fa2af80.pub'
      'sudo apt-get update'
      'sudo apt-get install cuda'

## Install Pytorch
      'conda install pytorch torchvision cudatoolkit=9.0 -c pytorch'
