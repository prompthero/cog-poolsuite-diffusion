# Poolsuite Diffusion for Replicate API

Model: [Poolsuite Diffusion](https://huggingface.co/prompthero/poolsuite-diffusion) 

Author: [@prompthero](prompthero.com)

## Instructions

First, `git clone` this repo and cd into it:
```console
git clone https://github.com/prompthero/cog-poolsuite-diffusion.git
cd cog-poolsuite-diffusion
```

### Download the weights:
```console
mkdir weights && cd weights
sudo apt-get install git-lfs
git lfs install
git clone https://huggingface.co/prompthero/poolsuite-diffusion
```

### Create a model in Replicate:

### Publish your model
````console
cog login
cog push r8.im/prompthero/poolsuite-diffusion 
````
 
