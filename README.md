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

## Week 4-5
### training a diffusion model 

* trained a diffusion model on fashion mnist dataset
* used unet2d model from diffusers library
* custom build noise scheduler class
* results are shown at the end of notebook inside week 4-5 directory

## Week 6
### training a u-net segmentation model

* trained a u-net model to segment images
* write custom code to select features to train the segmentation task

### Dataset
* [link](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge)

## Week 7
### training a denoising diffusion model 

* trained a ddpm model on fashion mnist dataset
* used unet2d model from [annoted diffusion unet](https://nn.labml.ai/diffusion/ddpm/unet.html)
* results are shown at the end of notebook inside week 7 directory
* conditional generation- ddpm model [link](https://www.kaggle.com/code/niteeshsingh/conditional-ddpm-model/edit)