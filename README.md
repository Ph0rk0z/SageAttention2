Sage attention hacked for NVIDIA Turing GPUs. See the real repo: https://github.com/thu-ml/SageAttention


MMA "fixed" thanks to https://github.com/1506086927

sparge attention can, in theory, run given the same treatment


------------------
Status as of 2.1.1:

Compiles on cuda 11.8

fused kernel : working on SM75

qattn: fixed MMA from https://github.com/1506086927

9/1/25 - triton w/fused works on ComfyUI with SageAttention command line.
12/13/25 - mma nan is fixed but speeds still not beating xformers when compiled
