# Documentation for Training Multi-Objective Variational Autoencoder for 3D Chair Dataset

**requirements.txt**

> A text file produced by pip describing the necessary python libs to reproduce the same virtual environment that is used for training. 
> ```shell
> pip freeze > requirements.txt  # The requirements file can be created by calling this command
> pip install -r requirements.txt  # The packages specified in the requirements file can be installed by pip by calling this command
> ```

**MoVAE_Chair.ipynb**

> * The most essential notebook for this project.
> * It contains code to automatically download the necessary dataset, pretrained vae model, and pretrained auxiliary discriminator models
> * See the notebook

**VAE_Chair.ipynb** 

> * In case one might want to train their own vae model instead of using pretrained vae model by researchers. 
> * See the notebook

**Auxiliary_Discriminators_Chair.ipynb** 

> * In case one might want to train their own auxiliary discriminators models instead of using pretrained models by researchers. 
> * See the notebook
