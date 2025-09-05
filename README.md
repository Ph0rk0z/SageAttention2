Sage attention hacked for NVIDIA Turing GPUs. See the real repo: https://github.com/thu-ml/SageAttention


MMA "fixed" thanks to https://github.com/mit-han-lab/nunchaku

qattn outputs are low quality but only tested SDXL
sparge attention can, in theory, run given the same treatment


------------------
Status as of 2.1.1:

Compiles on cuda 11.8

fused kernel : working on SM75

qattn: compiles and runs when selected (nans)

9/1/25 - triton w/fused works on ComfyUI with SageAttention command line.
