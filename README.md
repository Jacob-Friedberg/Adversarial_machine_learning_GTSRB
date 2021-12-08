# Adversarial_machine_learning_GTSRB

This project is an instructional notebook for adversarial machine learning using the GTSRB dataset.


In this notebook we will be learning how to do 3 tasks with Tensorflow/Keras:
1. Train a deep learning model using transfer learning on the German Traffic Sign Recognition Dataset GTSRB data set.
2. Implement 4 different white-box evasion attacks againts the model we trained, comparing their performances at different perturbation(ε) values
3. Implement a targeted white-box evasion attack using one of the attacks we have already implemented.
4. Implement a adversarial trainer defense for your model.

Each of theses tasks will be split up into their own sections with detailed descriptions of the methods used to implement each task. The goal of this notebook is to give you a beginners guide to techniques used in the adversarial machine learning field. You should be able to use what you've learned here to implement other attacks or defenses. Much of the machine learning field is rooted in research and most of the new machine learning and adversarial techniques are first published as papers. I highly suggest you go to the [arxiv][arxiv] website and check out the papers there. They are free to access and provide a great resource for those interested in the field.




### Requirments
This notebook relies on several packages to function.

Please install the following. Note: Please check the revision date on each of the links as they may be out of date

- Tensorflow 2.0 [Link][TFLOW]
- Numpy [Link][Numpy]
- MatPlotLib [Link][Plot]
- Pandas [Link][PANDA]
- h5py format [Link][h5]
- Adversarial Robustness ToolBox [Link][ART].

[//]: #
   [h5]:         <https://pypi.org/project/h5py/>
   [arxiv]: <https://arxiv.org/list/cs/recent>
   [TFLOW]: <https://www.tensorflow.org/install> 
   [Numpy]: <https://pypi.org/project/numpy/>
   [PANDA]: <https://pypi.org/project/pandas/>
   [Plot]: <https://pypi.org/project/matplotlib/>
   [ART]: <https://github.com/Trusted-AI/adversarial-robustness-toolbox>
    
    
    


# Attention
The dataset files are currently compressed using 7zip. Please uncompress the archives to their .P file format before use.

You are free to use the code as you please
