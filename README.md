# HPC_Bilateral_Filtering

# Assignment
Given the image of size M*N, implement and apply a CUDA version of 9-point bilateral filter and store the<br>
result to output image. Missing values for edge rows and columns are to be taken from nearest pixels. CUDA<br>
implementation must make use of texture memory.<br>

# Tools<br>
Programming language: Python v3.7.12<br>
IDE: Google Colaboratory<br>
GPU: Tesla K80<br>
CPU: Intel(R) Xeon(R) CPU @ 2.30GHz

# Images
## Image 1
Original Image | Bilateral CPU | Bilateral GPU | 
:----:|:----:|:----:|
![Screenshot](original.bmp) | ![Screenshot](cpu_output.bmp) | ![Screenshot](gpu_output.bmp) | 
|   | 108.20402<br>seconds|0.02473<br> seconds|

## Image 2
Original Image | Bilateral CPU | Bilateral GPU | 
:----:|:----:|:----:|
![Screenshot](original1.bmp) | ![Screenshot](cpu_output1.bmp) | ![Screenshot](gpu_output1.bmp) | 
|   | 7.99024<br>seconds|0.00278<br> seconds|



# Results
## Image 1
Bilateral CPU | Bilateral GPU | Boost
:----:|:----:|:----:|
108.20402<br>seconds|0.02473<br> seconds| 4375 |<br><br>

## Image 2
Bilateral CPU | Bilateral GPU | Boost
:----:|:----:|:----:|
7.99024<br>seconds|0.00278<br> seconds| 2873 |<br><br>


As a result of the work of the algorithms, an acceleration of the order of 4375 units was found for the first image and 2873 for the second image, which indicates the success of using the GPU.
