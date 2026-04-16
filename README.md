# FlashAttention 2.8.4 (CUDA 13.2 / Torch 2.12 / Triton 3.7)

Prebuilt FlashAttention wheel for modern NVIDIA GPUs (Blackwell / Ada / Hopper).

---

## 🚀 Download

👉 pip install --no-deps [https://github.com/CozzyTyler/flash-attn-cu132-wheel/releases/download/v2.8.4-cu132/flash_attn-2.8.4+cu132-cp312-cp312-linux_x86_64.whl](https://github.com/CozzyTyler/flash-attn-cu132-wheel/releases/download/v2.8.4-cu132-torch2.12-triton3.7/flash_attn-2.8.4+cu132-cp312-cp312-linux_x86_64.whl)

---

## ⚙️ Build info

- CUDA: 13.2  
- PyTorch: 2.12.0.dev (cu132 nightly)  
- Triton: 3.7  
- Python: 3.12  
- ABI: CXX11 (True)  

Built on RTX 5090 Laptop GPU (Blackwell).

---

## ⚠️ Important

This wheel is **NOT universal**.

It is compiled for a specific stack:

- Torch 2.12 (nightly)  
- CUDA 13.2  
- Triton 3.7  

👉 May NOT work on:

- stable PyTorch  
- older CUDA  
- different Triton  
- Python ≠ 3.12  

---

## 📦 Install

Download `.whl` from Releases and install:

```bash
pip install --no-deps flash_attn-2.8.4+cu132.torch2.12.triton3.7-cp312-linux_x86_64.whl
