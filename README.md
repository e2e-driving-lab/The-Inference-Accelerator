# The-Inference-Accelerator

Integration of General Purpose Training Infrastructures with the Inference Accelerator Using Open Source Compiler Toolchains
This paper proposes an open and hardware-independent architecture for connecting large-scale AI model training in the cloud with high-performance, low-latency inference on edge SoCs incorporating Rapidus GAA and Tenstorrent technologies.

The central concept is to use open-source compiler technologies and ONNX / ONNX Runtime Execution Providers (EPs) as a logical bridge between cloud-based training infrastructures and edge inference systems.
Furthermore, the architecture emphasizes portability and long‑term maintainability by ensuring that model optimization, graph partitioning, and kernel mapping remain decoupled from any specific semiconductor vendor or proprietary software stack.
