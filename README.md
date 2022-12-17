# sd-model-converter

convert stable diffusion model to fp16 / remove ema / safetensors

## Usage

```
python convert.py --f path/to/model.ckpt --half --no-ema --safe-tensors
```

before: 

Anything-V3.0.ckpt 7.17 GB  

after: 

anything-v3.0-prune.ckpt 3.97 GB  
anything-v3-prune-fp16.ckpt 1.98 GB  
anything-v3-prune-fp16.safetensors 1.98 GB  

![6N5O10P5 G7{~25GX7S A M](https://user-images.githubusercontent.com/36563862/208242262-dc0fb13e-8575-46ac-9557-b17d591e056a.png)