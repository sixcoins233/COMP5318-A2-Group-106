# COMP5318-A2-Group-106

For CPU running the model training part

It need software python 3.11 kernal in Anaconda Jupyter notebook

There is a running environment in env folder with all library we needed, 
Import it in Anaconda and open the Jupyter notebook to run all the codes.

There a part of important library
- tensorflow
- keras
- sklearn


----------------------------------------------

For GPU running the model training part (For nvidia GPU in Windows)

Install CUDA Toolkit 11.2 Update 2 version [download link](https://developer.nvidia.com/cuda-toolkit-archive)
Install cuDNN v8.1.1 [download link](https://developer.nvidia.com/rdp/cudnn-archive)

input "nvcc -V" to check CUDA version 
input ".\bandwidthTest.exe" ".\deviceQuery.exe" to check is it install successful

And then import the env in Anaconda just like above and run the code.