# Yolo_Pytorch
A Beginners Guide on using the Pytorch Implementation of YoloV4

   My experiments with YoloV4 where done on a MSI Laptop GP75 Leopard 9SE. It contains an NVIDIA Geforce RTX 2060 graphics card with 6 Gb of memory.

   The purpose of this repository is to document my experiences with training a convulutional neural network in hardware that is more consumer grade and acessible than some graphics cards that are normaly used in the YOLO papers.

   All code used comes from the repositories in the Acknowledgements section, and aditions or notes made my me will me explained further down.

---
# Acknowledgements
+ https://github.com/AlexeyAB/darknet

+ https://github.com/WongKinYiu/PyTorch_YOLOv4

+ https://github.com/WongKinYiu/ScaledYOLOv4

---
# Requirements
It is required you install CUDA and cuDNN before going through the instalation steps.

The instalation process is well described in the NVIDIA website.

+ CUDA Instalation guide: https://docs.nvidia.com/cuda/index.html

If you already know your system is compatible and capable of running CUDA you can just use the download link and install.

+ CUDA download: https://developer.nvidia.com/cuda-downloads

+ cuDNN Instalation Guide: https://docs.nvidia.com/deeplearning/cudnn/install-guide/index.html

+ cuDNN download: https://developer.nvidia.com/cudnn

---
# Instalation
1. Dowload the repository.

    `https://github.com/Duarte-Nunes/Yolo_Pytorch.git`
    
2. Install the Requirements.

    `cd Yolo_Pytorch`
    
    `pip install -r requirements.txt`
    
3. Make sure Pytorch is compiled with CUDA enabled
 
    Go to: https://pytorch.org/
    
    Run the command based on your system specifications
    
    ![alt text](https://github.com/Duarte-Nunes/Yolo_Pytorch/blob/main/images/pytorch_website.png "PyTorch Website")
    
---
# General Comands

## Detection

Commands avaiable on detect.py



## Testing

## Training
    
