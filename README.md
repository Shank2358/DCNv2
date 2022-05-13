# DCNv2_torch1.11

DCNv2 support torch1.11, amp, and onnx

fixed the bug of GPU allocation for distributed training


### Build
```bash
    ./make.sh         # build
    python testcpu.py    # run examples and gradient check on cpu
    python testcuda.py   # run examples and gradient check on gpu 
```
