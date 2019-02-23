# Ubuntu16.04查看CUDA和cuDNN版本
* cat /usr/local/cuda/version.txt
* cat /usr/local/cuda/include/cudnn.h | grep CUDNN_MAJOR -A 2

# Ubuntu16.04LTS下安装CUDA9.0和cuDNN7.0
1. 检查自己的计算机是否具备CUDA安装条件
    1. 检查GPU是否支持CUDA 
        * Windows下，可以通过NVIDIA GeForce Experience查看自己的GPU型号，或者通过百度、谷歌等搜索引擎来获取与自己PC相关的GPU信息。 
        * Linux下，可以在终端下键入
        > lspci | grep -i nvidia 