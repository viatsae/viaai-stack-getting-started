# VIAAI Stack Getting Started

### What is VIAAI Stack
VIAAI Stack is an installation package for popular deep learning framework, including Tensorflow, Keras, Pytorch, Caffe2, Caffe and CUDA. We simplify the installation procudure to one-line command. The AI Developer can focus on model development and training and don't worry about setting up the environment.

### On-line command installation
#### Ubuntu 18.04 / 16.04

```bash
wget http://archive.via.com.tw/viaai.sh && sudo chmod +x viaai.sh && \
sudo ./viaai.sh && sudo apt-get install -y viaai-stack
```

#### CentOS 7

```bash
sudo yum install wget epel-release -y && \
sudo wget http://archive.via.com.tw/viaai-stack.repo -O /etc/yum.repos.d/viaai-stack.repo && \
sudo yum install viaai-stack -y
```

### Upgrade to the latest VIAAI Stack version

#### Ubuntu 18.04 / 16.04
```
sudo apt-get update && sudo apt-get dist-upgrade && sudo apt-get autoremove
```
