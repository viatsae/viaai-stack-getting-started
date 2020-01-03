# VIAAI Stack Getting Started

### What is VIAAI Stack
VIAAI Stack is an installation package for popular deep learning framework, including Tensorflow, Keras, Pytorch, Caffe2, Caffe and CUDA. We simplify the installation procudure by apt-get command in Ubuntu. The AI Developer can focus on model development and training and don't worry about setting up the environment.

### Ubuntu 18.04 / 16.04 installation

* PREVIEW: Please add "211.23.178.200 archive.via.com.tw" to /etc/hosts/

```bash
wget http://archive.via.com.tw/viaai.sh && sudo chmod +x viaai.sh && \
sudo ./viaai.sh && sudo apt-get install viaai-stack
```

