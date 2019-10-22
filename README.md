# Pytorch implementation of the chamfer distance.

Include a *CUDA version*, and a *python version* with pytorch ops.

### CUDA VERSION

`chmod + x install.sh; ./install.sh`

Only support dimension 2, 3 or 5
Support multi-GPU

### Python Version

Supports any dimension

#### Comparison (1000 [forward + backward])

* Input1 : 32 x 2000 x 2

* Input2 : 32 x 1000 x 2

* Cuda -> 4 seconds, 500MB

* Python -> 30 seconds, 1GB 



#### TODO:

* Discuss behaviour of torch.min() and tensor.min() which causes issues in some pytorch versions

