PointPillars github
=============
https://github.com/zhulf0804/PointPillars

KITTI dataset download
-------------
https://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d

Anaconda install (Xavier only)
-------------
Hardware : Nvidia Jetson Xavier NX (aarch64) / OS : Jetpack 5.0.2-b231 (based on Ubuntu 20.04)
* * *
Jetson board 별로 호환이 되는 Anaconda의 버전이 다르기 때문에, 우리는 Mambaforge version을 사용해야함   
따라서 해당 링크에서 https://github.com/conda-forge/miniforge/releases   
Mambaforge-23.11.0-0-Linux-aarch64.sh download 받고   
##### install
- wget https://github.com/conda-forge/miniforge/releases/download/23.11.0-0/Mambaforge-23.11.0-0-Linux-aarch64.sh   
- sudo chmod 777 Mambaforge-23.11.0-0-Linux-aarch64.sh   
- sudo ./Mambaforge-23.11.0-0-Linux-aarch64.sh
##### 환경 변수 설정 (terminal)   
- export PATH=/home/viplab/Anaconda/bin:$PATH
- source ~/.bashrc -> 하게되면 conda version 확인 가능
##### gedit install
- sudo apt-get install gedit -y
##### gedit ~/.bashrc에서 환경변수 입력 후 저장   
- 가장 하단 부에 export PATH=/home/viplab/Anaconda/bin:$PATH 입력 및 저장
- source ~/.bashrc 하게되면 conda가 정상적으로 활성화 된 것을 확인 가능
##### torch install   
-  참고 링크 - https://yoonchang.tistory.com/25
-  sudo apt-get install python3-pip libopenblas-base libopenmpi-dev
-  pip3 install Cython numpy
-  Pytorch for Jetson 링크 - https://forums.developer.nvidia.com/t/pytorch-for-jetson/72048
-  wget torch-1.13.0a0+d0d6b1f2.nv22.10-cp38-cp38-linux_aarch64.whl 또는 링크에서 Download
-  pip3 install torch-1.13.0a0+d0d6b1f2.nv22.10-cp38-cp38-linux_aarch64.whl (*여기서 설치 위치는 /home이 되어야 설치 가능)   
-  pip install torchvision==0.14.0 torchaudio==0.13.0
-  sudo apt-get update   
