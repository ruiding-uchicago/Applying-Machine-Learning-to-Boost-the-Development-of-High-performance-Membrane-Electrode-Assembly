# The code file was write in jupyter notebook and saved in the corresponding format of .ipynb. To run the code, we suggest users to install Anaconda 3 in windows 10 and install the following necessary python packages with the same or higher version to set up compatible environment:
Python 3.7
jupyter 1.0.0
keras 2.3.1
numpy 1.18.1
pandas 1.0.1
scikit-learn 0.22.1
matplotlib 3.1.3
deep-belief-network 1.0.3
tensorflow-gpu 1.14.0
seaborn 0.10.0
R-Studio 8.13.176095 (for apriori algorithm)
Please notice that the computing of artificial neural network was runned on GPU. As GPUs generally shows better performance on machine learning especially deep learning tasks, manufacturers such as NVIDIA have designed dedicated packages to accelerate the computation. The device we utilized was NVIDIA GTX 2080ti. And CUDA 10.0/cuDNN7.6 released by NVIDIA to boost neuron network computing was also installed. Therefore, part of the original code that contains GPU memory assign might report error if tensorflow was computing on CPUs. Please remove the corresponding part if your environment is different. However, we should kindly remind you that the run time spent on the same code might be totally different as powerful hardwares could shorten the time to get the result hundredfold or even thousandfold. Please ensure your computing resource is qualified like computer clusters. Also, the important package-keras support another type of backend: Theano, the users are free to adjust with personal references.
 
