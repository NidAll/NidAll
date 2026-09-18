<div align="center">

# Nidhal // NidAll

`computer engineer · AI systems · Linux · inference optimization`

[![Linux](https://img.shields.io/badge/Linux-CachyOS-00E5FF?style=for-the-badge\&logo=linux\&logoColor=white)](https://cachyos.org/)
[![Python](https://img.shields.io/badge/Python-AI%20Tooling-D946EF?style=for-the-badge\&logo=python\&logoColor=white)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-Systems-E6EDF3?style=for-the-badge\&logo=rust\&logoColor=111111)](https://www.rust-lang.org/)
[![CUDA](https://img.shields.io/badge/CUDA-GPU%20Inference-00E5FF?style=for-the-badge\&logo=nvidia\&logoColor=white)](https://developer.nvidia.com/cuda-toolkit)

**I like making heavyweight AI models behave on hardware they were never supposed to fit on.**

</div>

---

## ⚡ What I build

| Project                                                                          | What it does                                                                                       | Focus                                                         |
| -------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| [**ComfyUI-Qwen3-TTS-Quant**](https://github.com/NidAll/ComfyUI-Qwen3-TTS-Quant) | Native ComfyUI runtime and streaming quantization toolkit for the full Qwen3-TTS 12 Hz 1.7B family | W8A8 ConvRot · packed INT8 · CUDA graphs · static KV caches   |
| [**comfyui-mixed-quantizer**](https://github.com/NidAll/comfyui-mixed-quantizer) | Diffusion and text-encoder quantization with stable W4A8 and experimental mixed-precision planning | W4A8 · W4A4 · INT8 · validation · memory-aware planning       |
| [**OpenCode 2 support for Ask**](https://github.com/benja/ask/pull/5)            | OpenCode 2 compatibility work for the Ask terminal AI client                                       | Rust · CLI integration · permissions · read-only agent design |

I spend a lot of time around the point where **model architecture, kernels, quantization, memory pressure, and runtime behavior** collide.

---

## 🧠 Engineering interests

**AI systems:** quantization, low-VRAM inference, CUDA kernels, memory residency, KV-cache design, graph capture, attention backends, and runtime optimization.

**Inference:** local LLMs, diffusion models, speech generation, multimodal systems, custom quantized runtimes, and squeezing maximum performance from constrained hardware.

**Linux:** rolling-release systems, terminal tooling, performance engineering, containers, and understanding the stack all the way down.

**Software engineering:** Rust, Python, systems integration, reproducible tooling, testing, and contributing fixes upstream.

---

## 🛠️ Current environment

```text
OS          CachyOS
Desktop     KDE Plasma
Terminal    Kitty
Shell       Fish

AI          ComfyUI · llama.cpp · PyTorch
GPU Stack   CUDA · FlashAttention · Comfy Kitchen
Languages   Python · Rust · C/C++
Dev         Git · GitHub · Docker · OpenCode
Terminal    micro · mdfried · ltop · lazydocker
```

I like tools that are **fast, composable, transparent, and close to the system**.

---

## 🔬 What I enjoy optimizing

```text
model
  ↓
architecture
  ↓
quantization
  ↓
kernel
  ↓
memory layout
  ↓
runtime
  ↓
benchmark
  ↓
repeat
```

If a model technically *shouldn't* fit, that usually makes it more interesting.

---

## 🐧 Beyond code

Linux is the playground. AI systems are the obsession.

I also enjoy **philosophy, mathematics, anime & manga, storytelling**, and two objectively excellent animals:

```text
   _~_        /\_/\
  (o o)      ( o.o )
 /  V  \      > ^ <
/(  _  )\
  ^^ ^^

 penguin       cat
```

My completely scientific rating scale:

**Ω > Z > S > A > B > C > D > F**

---

## 📊 GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=NidAll&show_icons=true&hide_border=true&bg_color=00000000&title_color=00E5FF&text_color=E6EDF3&icon_color=D946EF" height="165" alt="NidAll GitHub stats" />

<img src="https://streak-stats.demolab.com?user=NidAll&hide_border=true&background=00000000&ring=00E5FF&fire=D946EF&currStreakLabel=00E5FF&sideLabels=E6EDF3&currStreakNum=E6EDF3&sideNums=E6EDF3&dates=8B949E" height="165" alt="NidAll GitHub streak" />

</div>

---

<div align="center">

### Build it. Measure it. Understand why it works.

`Linux` · `AI` · `CUDA` · `Quantization` · `Systems`

</div>
