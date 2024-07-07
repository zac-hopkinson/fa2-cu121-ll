This is a pre-built wheel for flash-attn when running on Lambda Labs.

(At time of writing) Lambda Labs image runs Ubuntu 22.04 with CUDA 12.2 and Python 3.10.

I'm running PyTorch nightly (2.5.0) on it built for CUDA 12.1.

The flash-attn build takes around 20 minutes on this platform and I'm paying hourly on it.

Why do it this way? There are no pre-built wheels for PyTorch 2.5 CUDA 12.1 (mainly because it's a nightly release)
and I'm not aware of a better way to host a 100+MB binary for free.

