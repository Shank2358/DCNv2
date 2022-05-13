# DCNv2_torch1.11

DCNv2 support torch1.11, amp, and onnx

Fixed the bug of GPU allocation for distributed training

Thanks to [@haohaolalahao](https://github.com/haohaolalahao) for fixing these bugs.

感谢[@haohaolalahao](https://github.com/haohaolalahao)解决了DCNv2在torch1.10分布式训练时GPU ID分配bug和显存溢出bug。
该版本DCNv2支持torch1.10和1.11的分布式训练，支持AMP混合精度训练 和 ONNX转换

### Build
```bash
    ./make.sh         # build
    python testcpu.py    # run examples and gradient check on cpu
    python testcuda.py   # run examples and gradient check on gpu 
```
