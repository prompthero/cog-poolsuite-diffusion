# Lookbook by VisualHound for Replicate API

Model: [Lookbook](https://huggingface.co/prompthero/lookbook) 

Author: [@prompthero](prompthero.com)


### Download the weights:
##### For public models

```
$ mkdir weights
$ git lfs install
$ git clone https://huggingface.co/prompthero/lookbook
```
##### For private models
```
$ mkdir weights
$ git lfs install
$ pip install huggingface_hub
$ huggingface-cli login
$ git clone https://huggingface.co/prompthero/lookbook
```
### Create a model in Replicate

### Create a Docker and a cog image
```
$ docker build --tag lookbook .
$ cog build -t lookbook
``` 

### Publish your model
````
$ cog login
$ cog push r8.im/prompthero/lookbook 
````

