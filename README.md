# GPU-accelerated-n-body-simulations
CUDA based massively parallel 3D N-body simulation using Numba.
# 🚀 GPU-Accelerated 3D N-Body Simulation (CUDA + Numba)

## 📌 Overview

This project implements a massively parallel 3D gravitational N-body simulation using CUDA via Numba in Python.

The simulation computes O(N²) gravitational interactions between particles and executes them on the GPU using CUDA kernels.

---

## ⚙️ Technologies Used

- Python
- Numba (CUDA JIT)
- NVIDIA GPU
- NumPy
- Plotly (optional visualization)

---

## 🧠 GPU Concepts Demonstrated

- CUDA kernel programming
- SIMT execution model
- Thread/block configuration
- Explicit GPU memory transfers
- Device synchronization
- Parallel force computation

---

## 📊 Performance Benchmark

| Particles | Steps | CPU Time | GPU Time | Speedup |
|-----------|-------|----------|----------|----------|
| 800       | 200   | 0.145876 | 7.6896 | 52.7x |

---

## 🧮 Physics Model

- Newtonian gravitational force
- O(N²) brute-force interaction
- Simplified collision handling
- Energy monitoring

---


## 💡 Future Improvements

- Shared memory optimization
- Barnes–Hut algorithm (O(N log N))
- Multi-GPU scaling
- Nsight profiling
- C++ CUDA implementation
