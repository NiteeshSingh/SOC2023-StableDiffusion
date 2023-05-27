# SOC-2023 Stable Diffusion
## extra
* Build a custom training class named "Task" in the notebook, it has various cool fetures
    * we can continue training where we left previously
    * save oytput of each run in an separate folder
    * track and save best model and facility to save after every n epochs
    * keeps track of training loss, validation loss (other metrics can be easily added), in an history dictionary which is saved with model checkpoint
    * facility to validate in between after n epochs of trainng
    * add custom callbacks based on the validation result (working on it..)

## Week 1-2
[Notebook on kaggle](https://www.kaggle.com/code/niteeshsingh/resnet-for-pokemonclassification)
### building and training model in pytorch

* using resnet model for pokemon classification task
#### work done 
* used resnet model for pokemon classification
* achieved 37% accuracy on test, 46% on validation and 98% on test  (clearly overfitting, reduced dataset due to memory constraints)
* Tried using Transfer learning with finetuning
    * the task doesn't demand transfer learning infact it wasn't much effective in terms of accuracy because resnet was pretrained on ImageNet which have different domain than our pokemon datset (atleast that's what i reasoned out)

## Week 3
### training autoencoder and variational autoencoder

* training a autoencoder and variational autoencoder on fashion-mnist dataset
#### work done 

* trained a variational autoencoder on fashion-mnist dataset
* trained a variational autoencoder on fashion-mnist dataset
