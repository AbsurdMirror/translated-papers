# 已译论文

在线阅读：**https://absurdmirror.github.io/translated-papers/**

用 [pdf_agent_translator](https://github.com/AbsurdMirror/pdf_agent_translator) 生成的双语阅读稿。本仓**不含**阿里云 / LLM 密钥。

- 站点由 GitHub Pages（Actions）发布；`document.html` 须与 `figures/`、`source.pdf` 同目录。
- 改一处：阅读器「编辑 → 提议修改」开 Issue，或用本仓 Issue 模板。
- 维护者在 Issue 评论 `/apply`，会开 PR；也可本地 `pdf-translate apply-issue`。
- 源 PDF 一并提交。原文版权仍归作者/出版社。

仓库：https://github.com/AbsurdMirror/translated-papers

## 论文

### 0x01 微基准测试
- [0x01.1 · Demystifying GPU Microarchitecture through Microbenchmarking](https://absurdmirror.github.io/translated-papers/papers/gpu-microarchitecture/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/gpu-microarchitecture/source.pdf)
- [0x01.2 · Dissecting the NVIDIA Volta GPU Architecture via Microbenchmarking](https://absurdmirror.github.io/translated-papers/papers/0x01-2/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-2/source.pdf)
- [0x01.3 · Dissecting the NVidia Turing T4 GPU via Microbenchmarking](https://absurdmirror.github.io/translated-papers/papers/0x01-3/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-3/source.pdf)
- [0x01.4 · Demystifying the Nvidia Ampere Architecture through Microbenchmarking and Instruction-level Analysis](https://absurdmirror.github.io/translated-papers/papers/0x01-4/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-4/source.pdf)
- [0x01.5 · Low Overhead Instruction Latency Characterization for NVIDIA GPGPUs](https://absurdmirror.github.io/translated-papers/papers/0x01-5/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-5/source.pdf)
- [0x01.6 · Benchmarking and Dissecting the Nvidia Hopper GPU Architecture](https://absurdmirror.github.io/translated-papers/papers/0x01-6/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-6/source.pdf)
- [0x01.7 · Dissecting the NVIDIA Hopper Architecture through Microbenchmarking and Multiple Level Analysis](https://absurdmirror.github.io/translated-papers/papers/0x01-7/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-7/source.pdf)
- [0x01.8 · Dissecting and Modeling the Architecture of Modern GPU Cores](https://absurdmirror.github.io/translated-papers/papers/0x01-8/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-8/source.pdf)
- [0x01.9 · Microbenchmarking NVIDIA's Blackwell Architecture: An in-depth Architectural Analysis](https://absurdmirror.github.io/translated-papers/papers/0x01-9/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-9/source.pdf)
- [0x01.10 · Dissecting the NVIDIA Blackwell Architecture with Microbenchmarks](https://absurdmirror.github.io/translated-papers/papers/0x01-10/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x01-10/source.pdf)
### 0x02 ISA / SASS
- [0x02.1 · Decoding CUDA Binary](https://absurdmirror.github.io/translated-papers/papers/0x02-1/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x02-1/source.pdf)
- [0x02.2 · Optimizing Batched Winograd Convolution on GPUs](https://absurdmirror.github.io/translated-papers/papers/0x02-2/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x02-2/source.pdf)
- [0x02.3 · CuAsmRL: Optimizing GPU SASS Schedules via Deep Reinforcement Learning](https://absurdmirror.github.io/translated-papers/papers/0x02-3/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x02-3/source.pdf)
- [0x02.4 · SIP: Autotuning GPU Native Schedules via Stochastic Instruction Perturbation](https://absurdmirror.github.io/translated-papers/papers/0x02-4/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x02-4/source.pdf)
- [0x02.5 · Reverse-Engineering cuBLAS](https://absurdmirror.github.io/translated-papers/papers/0x02-5/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x02-5/source.pdf)
### 0x03 存储层次 / P-chase
- [0x03.1 · Dissecting GPU Memory Hierarchy through Microbenchmarking](https://absurdmirror.github.io/translated-papers/papers/0x03-1/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x03-1/source.pdf)
- [0x03.2 · Exploring Modern GPU Memory System Design Challenges through Accurate Modeling](https://absurdmirror.github.io/translated-papers/papers/0x03-2/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x03-2/source.pdf)
- [0x03.3 · TunneLs for Bootlegging: Fully Reverse-Engineering GPU TLBs for Challenging Isolation Guarantees of NVIDIA MIG](https://absurdmirror.github.io/translated-papers/papers/0x03-3/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x03-3/source.pdf)
- [0x03.4 · Dissecting Tensor Cores via Microbenchmarks: Latency, Throughput and Numeric Behaviors](https://absurdmirror.github.io/translated-papers/papers/0x03-4/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x03-4/source.pdf)
### 0x04 插桩
- [0x04.1 · NVBit: A Dynamic Binary Instrumentation Framework for NVIDIA GPUs](https://absurdmirror.github.io/translated-papers/papers/0x04-1/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x04-1/source.pdf)
- [0x04.2 · Flexible Software Profiling of GPU Architectures](https://absurdmirror.github.io/translated-papers/papers/0x04-2/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x04-2/source.pdf)
### 0x05 模拟器
- [0x05.1 · Analyzing CUDA Workloads Using a Detailed GPU Simulator](https://absurdmirror.github.io/translated-papers/papers/0x05-1/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x05-1/source.pdf)
- [0x05.2 · Accel-Sim: An Extensible Simulation Framework for Validated GPU Modeling](https://absurdmirror.github.io/translated-papers/papers/0x05-2/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x05-2/source.pdf)
- [0x05.3 · Need for Speed: Experiences Building a Trustworthy System-Level GPU Simulator](https://absurdmirror.github.io/translated-papers/papers/0x05-3/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x05-3/source.pdf)
- [0x05.4 · Mitigating GPU Core Partitioning Performance Effects](https://absurdmirror.github.io/translated-papers/papers/0x05-4/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x05-4/source.pdf)
- [0x05.5 · Analyzing and Improving Hardware Modeling of Accel-Sim](https://absurdmirror.github.io/translated-papers/papers/0x05-5/document.html) · [PDF](https://absurdmirror.github.io/translated-papers/papers/0x05-5/source.pdf)
