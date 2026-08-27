# Models and repos I used
A collection of huggingface models and github repos (with links) I used for private study

---

## 🛠️ 1. Fine-Tuning Tools

* **Kohya_ss (kohya-ss/sd-scripts / gui)**: GUI and training tools for fine-tuning Stable Diffusion and LoRAs.  
   [GitHub: bmaltais/kohya_ss](https://github.com/bmaltais/kohya_ss)
* **Fluxgym**: Lightweight Web UI for fine-tuning FLUX models and LoRAs.  
   [GitHub: cocktailpeanut/fluxgym](https://github.com/cocktailpeanut/fluxgym)

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
   [Hugging Face: mistralai/Devstral-Small-2505](mistralai/Devstral-Small-2505)
---


## 🎙️ 3. Voice Cloning

* **RVC (Retrieval-based Voice Conversion)**: Voice conversion framework based on VITS.  
   [GitHub: RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
* **GPT-SoVITS**: Zero-shot and few-shot TTS / Voice Cloning framework.  
   [GitHub: RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)  
  *(Note: Used to clone voice for teaching an online math course at UConn).*

---

## 🎨 4. Image Generation

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

## 🎭 5. Face Swapping
### Interface
* **FaceFusion**: Next-generation face swapper and enhancer tool.  
   [GitHub: facefusion/facefusion](https://github.com/facefusion/facefusion)

### Models & Libraries
* **inswapper_128**: ONNX face swapping model commonly integrated into face-swapping pipelines.  
   [Hugging Face: ApacheOne/insightface (inswapper_128.onnx)](https://huggingface.co/ApacheOne/insightface/blob/main/insightface/inswapper_128.onnx)
* **InsightFace**: 2D & 3D deep face analysis library for face detection, recognition, and swapping.  
   [GitHub: deepinsight/insightface](https://github.com/deepinsight/insightface)

---

## 🎁 Bonus: Low VRAM Platforms

* **WanGP (Wan2GP)**: Integrated platform by DeepBeepMeep designed to run video generation models (Wan, HunyuanVideo, LTX, Flux, etc.) efficiently on consumer GPUs with low VRAM footprint.  
   [GitHub: Decentralised-AI/Wan2GP](https://github.com/Decentralised-AI/Wan2GP)
