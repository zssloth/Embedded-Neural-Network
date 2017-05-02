# **Papers Reading List.**
- This is a collection of papers aiming at reducing model sizes or the ASIC/FPGA accelerator for Machine Learning, especially deep neural network related applications. (Inspiled by [Neural-Networks-on-Silicon](https://github.com/fengbintu/Neural-Networks-on-Silicon/blob/master/README.md))

## **Table of Contents**
- [Network Compression](#network-compression)
   - Parameter Sharing
   - Teacher-Student Mechanism (Distilling)
   - Fixed-precision training and storage
   - Sparsity regularizers & Pruning
   - Tensor Decomposition
   - Conditional (Adaptive) Computing
- [Hardware Accelerator](#hardware-accelerator)
   - Benchmark and Platform Analysis
   - Recurrent Neural Networks
   - Convolutional Neural Networks
- [Conference Papers](#conference-papers)
   - [2017 ICASSP](#2017-icassp)

##  **Network Compression**
### **Parameter Sharing**
- **structured matrices**
   - Structured Convolution Matrices for Energy-efficient Deep learning. (IBM Research–Almaden)
   - Structured Transforms for Small-Footprint Deep Learning. (Google Inc)
   - An Exploration of Parameter Redundancy in Deep Networks with Circulant Projections.
   - Theoretical Properties for Neural Networks with Weight Matrices of Low Displacement Rank.
- **Hashing**
   - Functional Hashing for Compressing Neural Networks. (Baidu Inc)
   - Compressing Neural Networks with the Hashing Trick. (Washington University + NVIDIA)
- Learning compact recurrent neural networks. (University of Southern California + Google)

### **Teacher-Student Mechanism (Distilling)**
- Distilling the Knowledge in a Neural Network. (Google Inc)
- Sequence-Level Knowledge Distillation. (Harvard University)

### **Fixed-precision training and storage**
- Deep neural networks are robust to weight binarization and other non-linear distortions. (IBM Research–Almaden)
   - XNOR-Net, Ternary Weight Networks (TWNs), Binary-net and their variants.
   - Recurrent Neural Networks With Limited Numerical Precision. (ETH Zurich + Montréal@Yoshua Bengio)
   - Neural Networks with Few Multiplications. (Montréal@Yoshua Bengio)
- 1-Bit Stochastic Gradient Descent and its Application to Data-Parallel Distributed Training of Speech DNNs. (Tsinghua University + Microsoft)
- Towards the Limit of Network Quantization. (Samsung US R&D Center)
- Incremental Network Quantization_Towards Lossless CNNs with Low-precision Weights. (Intel Labs China)
- Loss-aware Binarization of Deep Networks. (Hong Kong University of Science and Technology)
- Trained Ternary Quantization. (Tsinghua University + Stanford University + NVIDIA)

### **Sparsity regularizers & Pruning**
- Learning both Weights and Connections for Efficient Neural Networks. (SongHan, Stanford University)
- Deep Compression, EIE. (SongHan, Stanford University)
- Dynamic Network Surgery for Efficient DNNs. (Intel)
- Compression of Neural Machine Translation Models via Pruning. (Stanford University)
- Accelerating Deep Convolutional Networks using low-precision and sparsity. (Intel)
- Faster CNNs with Direct Sparse Convolutions and Guided Pruning. (Intel)
- Exploring Sparsity in Recurrent Neural Networks. (Baidu Research)
- Pruning Convolutional Neural Networks for Resource Efficient Inference. (NVIDIA)
- Pruning Filters for Efficient ConvNets. (University of Maryland + NEC Labs America)
- Soft Weight-Sharing for Neural Network Compression. (University of Amsterdam, [reddit discussion](https://www.reddit.com/r/MachineLearning/comments/5u7h3l/r_compressing_nn_with_shannons_blessing/))
- Sparsely-Connected Neural Networks_Towards Efficient VLSI Implementation of Deep Neural Networks. (McGill University)
- Training Compressed Fully-Connected Networks with a Density-Diversity Penalty. (University of Washington)

### **Tensor Decomposition**
- Compression of Deep Convolutional Neural Networks for Fast and Low Power Mobile Applications. (Samsung, etc)
- Learning compact recurrent neural networks. (University of Southern California + Google)
- Tensorizing Neural Networks. (Skolkovo Institute of Science and Technology, etc)
- Ultimate tensorization_compressing convolutional and FC layers alike. (Moscow State University, etc)
- Efficient and Accurate Approximations of Nonlinear Convolutional Networks. (@CVPR2015)
- Exploiting Linear Structure Within Convolutional Networks for Efficient Evaluation. (New York University, etc.)
- Convolutional neural networks with low-rank regularization. (Princeton University, etc.)
- **Learning with Tensors: Why Now and How?** (Tensor-Learn Workshop @ NIPS'16)

##  **Conditional (Adaptive) Computing**
- Adaptive Computation Time for Recurrent Neural Networks. (Google DeepMind@Alex Graves)
- Variable Computation in Recurrent Neural Networks. (New York University + Facebook AI Research)
- Spatially Adaptive Computation Time for Residual Networks. ([github link](https://github.com/mfigurnov/sact) Google, etc.)
- Hierarchical Multiscale Recurrent Neural Networks. (Montréal)
- Outrageously Large Neural Networks_The Sparsely-Gated Mixture-of-Experts Layer. (Google Brain, etc.)
- Adaptive Neural Networks for Fast Test-Time Prediction. (Boston University, etc)
- Dynamic Deep Neural Networks_Optimizing Accuracy-Efficiency Trade-offs by Selective Execution. (University of Michigan)
- **Estimating or Propagating Gradients Through Stochastic Neurons for Conditional Computation**. (@Yoshua Bengio)
## **Hardware Accelerator**
### **Benchmark and Platform Analysis**
- Fathom: Reference Workloads for Modern Deep Learning Methods. (Harvard University)
- DeepBench: Open-Source Tool for benchmarking DL operations. (svail.github.io-Baidu)

### **Recurrent Neural Networks**
- FPGA-based Low-power Speech Recognition with Recurrent Neural Networks. (Seoul National University)
- Accelerating Recurrent Neural Networks in Analytics Servers: Comparison of FPGA, CPU, GPU, and ASIC. (Intel)
- ESE: Efficient Speech Recognition Engine with Compressed LSTM on FPGA. (Song Han, Stanford University, etc.)

### **Convolutional Neural Networks**
- Caffeinated FPGAs: FPGA Framework For Convolutional Neural Networks
- Accelerating Binarized Neural Networks: Comparison of FPGA, CPU, GPU, and ASIC. (Intel)
- FINN: A Framework for Fast, Scalable Binarized Neural Network Inference. (Xilinx Research Labs, etc.)

## **Conference Papers**

### **2017 ICASSP**
-	lognet: energy-efficient neural networks using logarithmic computation
-	investigations on byte-level convolutional neural networks for language modeling in low resource speech recognition
-	extended low rank plus diagonal adaptation for deep and recurrent neural networks
-	fixed-point optimization of deep neural networks with adaptive step size retraining
-	harnessing neural networks: a random matrix approach
-	implementation of efficient, low power deep neural networks on next-generation intel client platforms
-	low-rank and sparse soft targets to learn better dnn acoustic models
-	knowledge distillation for small-footprint highway networks
-	exploiting sequential low-rank factorization for multilingual dnns
-	the group k-support norm for learning with structured sparsity
-	automatic node selection for deep neural networks using group lasso regularization
-	accelerating deep convolutional networks using low-precision and sparsity
