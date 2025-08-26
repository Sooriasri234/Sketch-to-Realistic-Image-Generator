# 🎨 Sketch-to-Realistic Image Generator

This project converts hand-drawn sketches into **realistic images** using **Stable Diffusion v1.5** with **ControlNet (Scribble)**.  
It provides a **Gradio web interface** where users can upload a sketch, enter a prompt, and generate high-quality, realistic images.

---

## 🚀 Features
- 🖼️ Upload a **sketch** and generate realistic results
- 📝 Provide a **text prompt** to guide generation
- ⚡ Powered by **Stable Diffusion** + **ControlNet**
- 🌐 Simple and interactive **Gradio UI**
- 💻 Works on GPU-enabled environments like **Google Colab**

---

## 🛠️ Tech Stack
- [Python](https://www.python.org/)
- [PyTorch](https://pytorch.org/)
- [Diffusers](https://huggingface.co/docs/diffusers/index)
- [Transformers](https://huggingface.co/docs/transformers/index)
- [Gradio](https://www.gradio.app/)
- [OpenCV](https://opencv.org/)

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Sooriasri234/Sketch-to-Realistic-Image-Generator.git
cd Sketch-to-Realistic-Image-Generator

# Install required libraries
pip install diffusers transformers accelerate opencv-python gradio
