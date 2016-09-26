# **Papers Reading List.**
- This is a collection of papers aiming at reducing model sizes or the ASIC/FPGA accelerator for Machine Learning, expecially deep neural network related applications. (Inspiled by [Neural-Networks-on-Silicon](https://github.com/fengbintu/Neural-Networks-on-Silicon/blob/master/README.md))
- Notes can be found in my personal [blog](https://zhishengwang.github.io/Neural-Network-Notes/). (**TODO**)
- New commits will mark with blue.

##  **Network Compression**

### **Parameter Sharing**
- **structured matrices**
   - Structured Convolution Matrices for Energy-efficient Deep learning. (IBM Research–Almaden)
   - Structured Transforms for Small-Footprint Deep Learning. (Google Inc)
   - An Exploration of Parameter Redundancy in Deep Networks with Circulant Projections.
- **Hashing**
   - Functional Hashing for Compressing Neural Networks. (Baidu Inc)
   - Compressing Neural Networks with the Hashing Trick. (Washington University + NVIDIA)

### **Teacher-Student Mechanism (Distilling)**
- Distilling the Knowledge in a Neural Network. (Google Inc)

### **Fixed-precision training and storage**
- Deep neural networks are robust to weight binarization and other non-linear distortions. (IBM Research–Almaden)
   - XNOR-Net, Ternary Weight Networks (TWNs), Binary-net and their variants.
   - Recurrent Neural Networks With Limited Numerical Precision. (ETH Zurich + Montréal@Yoshua Bengio)
   - Neural Networks with Few Multiplications. (Montréal@Yoshua Bengio)
- 1-Bit Stochastic Gradient Descent and its Application to Data-Parallel Distributed Training of Speech DNNs. (Tsinghua University + Microsoft)

### **Sparsity regularizers & Pruning**
- Learning both Weights and Connections for Efficient Neural Networks. (SongHan, Stanford University)
- Deep Compression, EIE. (SongHan, Stanford University)
- Dynamic Network Surgery for Efficient DNNs. (Intel)

### **Low-rank matrix factorization**

##  **Conditional Computing**
- Adaptive Computation Time for Recurrent Neural Networks. (Google DeepMind@Alex Graves)

## **Hardware Accelerator**
### **Benchmark and Platform Analysis**
- Fathom: Reference Workloads for Modern Deep Learning Methods. (Harvard University)
- Accelerating Recurrent Neural Networks in Analytics Servers: Comparison of FPGA, CPU, GPU, and ASIC. (Intel)
- <font color=blue>Accelerating Binarized Neural Networks: Comparison of FPGA, CPU, GPU, and ASIC. (Intel)</font>
