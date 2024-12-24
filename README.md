# Tegrastats parser

Parse tegrastats lines such as: 

```bash
12-23-2024 22:54:11 RAM 3162/7620MB (lfb 4x2MB) SWAP 0/3810MB (cached 0MB) 
CPU [1%@729,0%@729,0%@729,0%@729,off,off] GR3D_FREQ 1% cpu@62.843C soc2@61.968C soc0@60.625C gpu@61.687C tj@62.843C soc1@61.687C 
VDD_IN 3913mW/3922mW VDD_CPU_GPU_CV 598mW/598 VDD_SOC 1238mW/1237mW
```

For the FSW, the processed data will be written to a shared memory block.