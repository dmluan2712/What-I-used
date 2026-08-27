# Models and repos I used
A collection of huggingface models and github repos (with links) I used for private study

---

## 🛠️ 1. Fine-Tuning Tools

* **Kohya_ss (kohya-ss/sd-scripts / gui)**: GUI and training tools for fine-tuning Stable Diffusion and LoRAs.  
   [GitHub: bmaltais/kohya_ss](https://github.com/bmaltais/kohya_ss)
* **Fluxgym**: Lightweight Web UI for fine-tuning FLUX models and LoRAs.  
   [GitHub: cocktailpeanut/fluxgym](https://github.com/cocktailpeanut/fluxgym)

---

## 💬 2. Local LLMs (Large Language Models)

### Interface
* **KoboldCPP**: Lightweight, cross-platform UI and API server for running local LLMs.  
   [GitHub: LostRuins/koboldcpp](https://github.com/LostRuins/koboldcpp)

### Models
* **Qwen 2.5 / Qwen 3.5 Series**:  
   [Hugging Face: Qwen/Qwen2.5-7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-7B-Instruct)
* **Mistral NeMo 12B**:  
   [Hugging Face: mistralai/Mistral-Nemo-Instruct-2407](https://huggingface.co/mistralai/Mistral-Nemo-Instruct-2407)
* **Devstral series**:
   [Hugging Face: mistralai/Devstral-Small-2505](https://huggingface.co/mistralai/Devstral-Small-2505)

---


## ⚡ 3. VRAM & Attention Optimization Tools

*(Crucial for running large diffusion or language models on modest VRAM setups like an 8GB GPU).*

* **FlashAttention**: An IO-aware exact attention algorithm that drastically speeds up attention computations and reduces memory overhead from quadratic to linear scaling by leveraging GPU hardware hierarchy (SRAM/HBM tiling).  
   [GitHub: Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention)  
   **Paper**: *FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness* (Dao et al., 2022) — [arXiv:2205.14135](https://arxiv.org/abs/2205.14135)

* **SageAttention**: A plug-and-play low-bit (8-bit / 4-bit) attention quantization framework that accelerates model inference with virtually no loss in end-to-end metric quality.  
   [GitHub: aagroup/SageAttention](https://github.com/aagroup/SageAttention)  
   **Paper**: *SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration* (Zhang et al., 2024) — [arXiv:2410.02367](https://arxiv.org/abs/2410.02367)

* **Triton (OpenAI Triton)**: A C-like Python-based programming language and compiler that enables developers to write highly optimized custom GPU kernels without direct low-level CUDA programming.  
   [GitHub: triton-lang/triton](https://github.com/triton-lang/triton)  
   **Paper**: *Triton: An Intermediate Language and Compiler for Tile-Based Neural Network Generators* (Tillet et al., 2019) — [MAPL '19 Conference Proceedings](https://dl.acm.org/doi/10.1145/3315508.3329973)

## 🎙️ 4. Voice Cloning

* **RVC (Retrieval-based Voice Conversion)**: Voice conversion framework based on VITS.  
   [GitHub: RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
* **GPT-SoVITS**: Zero-shot and few-shot TTS / Voice Cloning framework.  
   [GitHub: RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)  
  *(Note: Used to clone voice for teaching an online math course at UConn).*

---

## 🎨 5. Image Generation

### Interfaces & Workflows
* **ComfyUI**: Node-based graphical interface for customizable image generation workflows.  
   [GitHub: comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)
* **AUTOMATIC1111**: Web UI for Stable Diffusion models.  
   [GitHub: AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

### Base Models
* **Stable Diffusion 1.5**:  
   [Hugging Face: runwayml/stable-diffusion-v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5)
* **Stable Diffusion XL (SDXL 1.0)**:  
   [Hugging Face: stabilityai/stable-diffusion-xl-base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
* **Stable Diffusion 3.5**:  
   [Hugging Face: stabilityai/stable-diffusion-3.5-large](https://huggingface.co/stabilityai/stable-diffusion-3.5-large)
* **FLUX.1 [dev]**:  
   [Hugging Face: black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)
* **FLUX.2 [klein]**:  
   [Hugging Face: black-forest-labs/FLUX.2-klein-9B](https://huggingface.co/black-forest-labs/FLUX.2-klein-9B)
* **Z-Image Base**: High-realism image generation model with sharp details.  
   [Hugging Face: sinatra-rd/real-dream-z-image-de-turbo-beta](https://huggingface.co/sinatra-rd/real-dream-z-image-de-turbo-beta)

### Fine-Tuned Models
* **CyberRealistic**:  
   [Hugging Face: CyberRealistic/CyberRealistic](https://huggingface.co/CyberRealistic/CyberRealistic)
* **Realistic Vision**:  
   [Hugging Face: SG161222/Realistic_Vision_V5.1_noVAE](https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE)
---

### Video Generators
* **LTX-Video**: DiT-based real-time video generation model by Lightricks.  
   [GitHub: Lightricks/LTX-Video](https://github.com/Lightricks/LTX-Video)  
   [Hugging Face: Lightricks/LTX-Video](https://huggingface.co/Lightricks/LTX-Video)
* **Wan (Wan2.1 / Wan2.2)**: Open video generation model family developed by Wan-AI.  
   [GitHub: Wan-Video/Wan2.1](https://github.com/Wan-Video/Wan2.1)  
   [Hugging Face: Wan-AI](https://huggingface.co/Wan-AI)
* **HunyuanVideo**: High-quality open-source video generation framework by Tencent.  
   [GitHub: Tencent-Hunyuan/HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo)  
   [Hugging Face: tencent/HunyuanVideo](https://huggingface.co/tencent/HunyuanVideo)

---

## 🎭 6. Face Swapping
### Interface
* **FaceFusion**: Next-generation face swapper and enhancer tool.  
   [GitHub: facefusion/facefusion](https://github.com/facefusion/facefusion)

### Models & Libraries
* **inswapper_128**: ONNX face swapping model commonly integrated into face-swapping pipelines.  
   [Hugging Face: ApacheOne/insightface (inswapper_128.onnx)](https://huggingface.co/ApacheOne/insightface/blob/main/insightface/inswapper_128.onnx)
* **InsightFace**: 2D & 3D deep face analysis library for face detection, recognition, and swapping.  
   [GitHub: deepinsight/insightface](https://github.com/deepinsight/insightface)

---

## ⚙️ 7. Model Quantization Tools & Resources

* **`llama.cpp` (`llama-quantize`)**: The premier C/C++ engine and toolkit for quantizing LLMs into the GGUF format across various bit-widths (e.g., `Q4_K_M`, `Q5_K_M`, `Q8_0`).  
   [GitHub: ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp)  
   **GGUF Format Overview**: *GGUF Specification and Quantization Design* — [GGUF Specification](https://github.com/ggerganov/ggml/blob/master/docs/gguf.md) / [IST-DASLab GPTQ-GGUF Paper](https://github.com/IST-DASLab/gptq-gguf-toolkit)

* **INT8 Quantization Theory & Practice**: Uniform integer quantization maps high-precision floating-point weights ($FP32$/$FP16$) down to $INT8$ precision, offering up to $4\times$ memory footprint reduction with minimal degradation in model accuracy.  
   **Paper**: *A White Paper on Neural Network Quantization* (Nagel et al., 2021) — [arXiv:2106.08295](https://arxiv.org/abs/2106.08295)  
   **Paper**: *Integer Quantization for Deep Learning Inference: Principles and Empirical Evaluation* (Wu et al., 2020) — [arXiv:2004.09602](https://arxiv.org/abs/2004.09602)

* **Quantization Scheme Comparisons**:  
   [Hugging Face Quantization Guide & Method Overview](https://huggingface.co/docs/transformers/main_classes/quantization) — Comprehensive comparison comparing `bitsandbytes` ($INT8$/$FP4$), `GPTQ`, `AWQ`, `AQLM`, and `GGUF` precision, speed, VRAM consumption, and quality trade-offs.

---
## 🎁 Bonus: Low VRAM Platforms

* **WanGP (Wan2GP)**: Integrated platform by DeepBeepMeep designed to run video generation models (Wan, HunyuanVideo, LTX, Flux, etc.) efficiently on consumer GPUs with low VRAM footprint.  
   [GitHub: Decentralised-AI/Wan2GP](https://github.com/Decentralised-AI/Wan2GP)
