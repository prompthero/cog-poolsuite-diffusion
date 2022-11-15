# Poolsuite Diffusion for Replicate API

Model: [Poolsuite Diffusion](https://huggingface.co/prompthero/poolsuite-diffusion) 

Author: [@prompthero](prompthero.com)


### Download the weights:
> git lfs install
>
> git clone https://huggingface.co/prompthero/poolsuite-diffusion

### Create a model in Replicate:

In the last line of `prediction.py`:
``` 
image: "r8.im/yourUser/yourModelName" 
```

### Publish your model
> cog login
>
> cog push
