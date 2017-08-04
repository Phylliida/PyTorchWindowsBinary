# PyTorchWindowsBinary
Precompiled binaries for PyTorch with CUDA for Python 3.5 on Windows x64

Install via

```
pip3 install torch-0.1.12-cp35-cp35m-win_amd64.whl
```

Depending on your setup you might also need to add the dlls in bin to lib/site-packages/torch/lib in your python dir.

If you are having any issues with this it might be easier to try [peterjc123's build](https://github.com/pytorch/pytorch/issues/494) instead. The only downside is that that build is CPU only.
