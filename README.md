The properties of a compute device, which can used for knowing how much memory
and what capabilities the device has.

```c
1. Check how many compute devices are attached.
2. List some properties of each device.
```

```bash
# OUTPUT
COMPUTE DEVICE 0:
Name: GeForce GTX 1050
Compute capability: 6.1
Multiprocessors: 5
Clock rate: 1493 MHz
Global memory: 4096 MB
Constant memory: 64 KB
Shared memory per block: 48 KB
Registers per block: 65536
Threads per block: 1024 (max)
Threads per warp: 32
Block dimension: 1024x1024x64 (max)
Grid dimension: 2147483647x65535x65535 (max)
Device copy overlap: yes
Kernel execution timeout: yes
```

See [main.cu] for code.

[main.cu]: main.cu


### references

- [CUDA by Example :: Jason Sanders, Edward Kandrot](http://www.mat.unimi.it/users/sansotte/cuda/CUDA_by_Example.pdf)
