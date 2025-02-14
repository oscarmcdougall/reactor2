# ReActor2 for Stable Diffusion 🎭✨

[![Version](https://img.shields.io/badge/version-2.0.0-green?style=for-the-badge&labelColor=darkgreen)](#)  
**Support the Project:** [Boosty](https://boosty.to/artgourieff) 💖

---

## What’s New in ReActor2 🚀
- **Enhanced FaceSwap:** Even faster, more accurate swaps with improved multi-face detection.  
- **Dynamic Controls:** Fine-tune face model selections, blending, and post-processing order effortlessly.  
- **Robust API:** Seamless integration for both internal and external POST/GET requests.  
- **Expanded Compatibility:** Now supports AUTOMATIC1111, SD.Next, Cagliostro Colab UI, and ComfyUI.  
- **Optimised Performance:** Superior speed on CPUs and GPUs alike, with CUDA 12 acceleration.

---

## Quick Installation 🛠️
**For AUTOMATIC1111/SD WebUI Forge:**  
1. Install Visual Studio or VS C++ Build Tools.  
2. In the "Extensions" tab, search for or install via URL:  
   `https://github.com/Gourieff/sd-webui-reactor`  
3. Restart the UI as prompted.

**For SD.Next & Colab UI:**  
1. Activate your virtual environment and install dependencies (`insightface==0.7.3`).  
2. Add ReActor2 via URL, adjust model file locations if needed, and restart.

---

## Key Features 🌟
- **Lightning-Fast Face Swaps:** Swap faces with precision, supporting multiple faces and gender-specific swaps.  
- **Image Enhancements:** Restore, upscale, and blend faces with advanced mask correction.  
- **Smart Models:** Save and load lightweight safetensors face models for quick re-use.  
- **API & Customisation:** Leverage powerful API endpoints and tweak processing pipelines to suit your needs.

---

## How to Use 🎨
1. **Import:** Choose an image from the "ReActor2" menu.  
2. **Activate:** Tick the "Enable" box and select desired options (face indexes, restoration, etc.).  
3. **Process:** Watch as ReActor2 delivers a refined, enhanced face swap!

---

## Troubleshooting & Support 🔧
- **Missing Model Files?** Ensure `inswapper_128.onnx` is in the `models/insightface` folder.  
- **Installation Issues?** Update pip and reinstall dependencies (e.g. `insightface`, `onnxruntime-gpu`).  
- **API or Extension Conflicts?** Disable overlapping face swap tools and check our [GitHub Issues](https://github.com/Gourieff/sd-webui-reactor/issues).

---

## Disclaimer ⚠️
ReActor2 is designed for ethical, non-commercial research and creative use. Always obtain consent when using real faces and clearly label deepfakes. The pre-trained models are for non-commercial research only. Developers are not liable for misuse.

---

Happy face swapping with ReActor2! 😎