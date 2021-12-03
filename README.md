# HPC_Bilateral_Filtering

# Задание
Given the image of size M*N, implement and apply a CUDA version of 9-point bilateral filter and store the<br>
result to output image. Missing values for edge rows and columns are to be taken from nearest pixels. CUDA<br>
implementation must make use of texture memory.<br>

# Программные и аппаратные срвества<br>
Язык программирования: Python v3.7.12<br>
IDE: Google Colaboratory<br>
GPU: Tesla K80<br>
CPU: Intel(R) Xeon(R) CPU @ 2.30GHz

# Картинки
Original Image | Bilateral CPU | Bilateral GPU | 
:----:|:----:|:----:|
![Screenshot](original.bmp) | ![Screenshot](cpu_output.bmp) | ![Screenshot](gpu_output.bmp) | 
|   | 108.20402<br>seconds|0.02473<br> seconds|

# Результаты
Bilateral CPU | Bilateral GPU | Boost
:----:|:----:|:----:|
108.20402<br>seconds|0.02473<br> seconds| 4375 |<br><br>

В результате работы алгоритмов было выявлено ускорение пордяка 4375 единиц, что говорит об успешности применении GPU. 
