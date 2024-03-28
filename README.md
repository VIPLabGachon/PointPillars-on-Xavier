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
1. wget https://github.com/conda-forge/miniforge/releases/download/23.11.0-0/Mambaforge-23.11.0-0-Linux-aarch64.sh   
2. sudo chmod 777 Mambaforge-23.11.0-0-Linux-aarch64.sh   
3. sudo ./Mambaforge-23.11.0-0-Linux-aarch64.sh
##### 환경 변수 설정 (terminal)   
4. export PATH=/home/viplab/Anaconda/bin:$PATH
5. source ~/.bashrc -> 하게되면 conda version 확인 가능
##### gedit install
6. sudo apt-get install gedit -y
##### gedit ~/.bashrc에서 환경변수 입력 후 저장   
7. 가장 하단 부에 export PATH=/home/viplab/Anaconda/bin:$PATH 입력 및 저장
8. source ~/.bashrc 하게되면 conda가 정상적으로 활성화 된 것을 확인 가능
##### Conda install   
9. 
