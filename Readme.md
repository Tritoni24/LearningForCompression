# SEQNOC_MOD
The Implementation for the IEEE Access paper "Lossless Compression of Point Cloud Sequences Using Sequence Optimized CNN Models"

The original code is available in the author's repository: https://github.com/marmus12/seqnoc
The main changes proposed in this repo are:
* Support for different HW (CUDA or CPU)
* NaN issue in the optimization step when changing batch size or trying to compress different sequences than 8iVFB
* Support for pre-trained CNN input to avoid training each time.


Requirements:
* PyTorch (tested with version 1.10.2)
* Open3D
* TorchAC (https://github.com/fab-jul/torchac)
