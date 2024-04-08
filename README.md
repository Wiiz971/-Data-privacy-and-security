# 隱私資訊安全 - Deep Learning with Differential Privacy

#### General Informations :

* [Depôt Github](https://github.com/Wiiz971/Data-privacy-and-security/)
   In this report we use github – Deep Learning with Differential Privacy to implement the differential privacy in deep learning.
At the beginning, we focus on the code on github to do research, find the place to set the parameters, and where the main functions are, then we change the parameters that will be used in the experiment, through the change of different parameters, we can observe the effect of the parameters on the Accuracy and the relationship between epcoh and epsilon.

* Collaborators  :
    *  [Vincent AZINCOURT](https://github.com/Wiiz971)
    *  [朱亭宇](https://github.com/jsp)
    *  [游騰毅](https://github.com/jsp)
    *  [陳威](https://github.com/jsp)
    *  [高瑜](https://github.com/jsp)
* Highly inspired by [lingyunhao](https://github.com/lingyunhao)'s code.

## Prerequisites
Windows 10 + CUDA 10 + CUDNN 7 + TensorFlow 2.0 with Anaconda 3
```
conda create -n tf2 python=3.6
activate tf2
conda install tensorflow-gpu==2.0.0
pip install tensorflow-privacy==0.1.0
```

* Tools used for the project :
    * [Python 3.6.15](https://www.python.org/downloads/release/python-3615/)
    * [Spider version 5.1.5](https://www.spyder-ide.org/)
    * `numpy`==1.25.1
    * `torch`==2.0.1
    * `scipy` >= 0.17
    * `mpmath` (for testing)
    * `tensorflow_datasets` (for the RNN tutorial `lm_dpsgd_tutorial.py` only)
    * `pytorch-lightning`==2.0.6
    * `tensorflow-gpu`==2.0.0
    * `tensorflow-privacy`==0.1.0
    * `tensorboard`==2.14.0
 
  
