# Tensorflow <br>
It's all about learning Tensorflow <br>
## install tensorflow on last version of anaconda  windows<br>
### tensorflow=2<br>
The first stage<br>
conda create --name tf2 python = 3.7<br>

second stage<br>
Conda activate tf2<br>

third level<br>
conda install tensorflow<br>
That installs version 2 of tensorflow.<br>
The fourth stage<br>
Here's a recipe that will always appear in Jupyter after creating an environment with the same name.<br>
Running this command is only enough once.<br>
conda activate base<br>
The fifth step<br>
pip install ipykernel<br>
Step Six<br>
conda install nb_conda_kernels<br>
 Now you have to get it done and make sure that the body is properly installed before you go to Jupiter here<br>
conda activate tf2<br>
Then<br>
python<br>
Now in the new environment you can only enter the Python code<br>

import tensorflow as tf<br>

Then, if this line is executed, we will see the version of Tansorflow<br>
tf .__ version__<br>

Now to get out of Python<br>
quit ()<br>
### tensorflow=1.14<br>
Now, if you need to get used to tensorflow 1 . we'll start building the environment again.<br>
If you want to install Tensorflow 1.14, I heard Python 3.6 is good then:<br>

conda create --name tf1.14 python = 3.6<br>

conda activate tf.1.14<br>

conda install tensorflow = 1.14<br>

And because of those previous codes, now the environment has gone to Jupyter<br>
To check here<br>
python<br>
import tensorflow as tf<br>
tf .__ version__<br>
And finally<br>

quit ()<br>
### tensorflow=1<br>
If you want the latest version of Tensorflow=1<br>
conda create --name tf1 python = 3.7<br>

conda install tensorflow = 1<br>

And because of those previous codes, now the environment has gone to Jupiter<br>
To check here<br>
python<br>
import tensorflow as tf<br>
tf .__ version__<br>
And finally<br>

quit ()<br>
Now that you want to check in Jupiter<br>
jupyter notebook<br>
