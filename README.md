# lucifer

My PyTorch environment and all dependencies to run experiments for digital pathology.

## Requirements
A requirments.txt file has been provided so you can install all the relevant dependencies for these extraction methods. Navigate to the directory contaning this file and type the following command in your terminal to install these packages:

~~~
pip install -r requirements.txt
~~~

## PyTorch 
Here is the link to install PyTorch:
https://pytorch.org/

On my macbook I already have Anaconda installed so can "conda" install packages.
For no GPU, I install via:

~~~
conda install pytorch torchvision -c pytorch
~~~

On my Linux computer I already have CUDA and its toolkit installed (version 10.1, it might be 9.2 so check). For use on GPUs, install via:

~~~
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
~~~
