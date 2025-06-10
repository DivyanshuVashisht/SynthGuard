# 🛡️ SynthGuard – Generative AI for Anomalous Event Simulation

**SynthGuard** is a lightweight prototype that simulates rare or unusual events as short videos, based entirely on text prompts. It uses Stable Diffusion to generate sequential image frames and stitches them into a playable video.

---

## 🚀 Features

- 🧠 **Text-to-video generation** using Stable Diffusion
- 🖼️ **5–10 frame sequences** for fast prototyping
- 📽️ **Video playback in-stream** for quick visualization
- ⚡ Lightweight, GPU-accelerated (via Google Colab)

---

## 🧰 Tech Stack

- **Python**
- **Stable Diffusion** via 🤗 `diffusers`
- `ffmpeg-python` for video assembly
- `Streamlit` for optional UI (separate deployment)
- **Google Colab** for GPU-backed runtime

---

## 🛠️ Setup

👉 Use the project directly in **Google Colab**:  
📎 [**Run SynthGuard on Colab**](https://colab.research.google.com/drive/1ghWV8ZlCD_KfYQIdKh6xCq4S1dwDDrQT?usp=sharing)

No installation required — just open the link and run each cell in sequence.

---

## 💡 Future Improvements

Here are some ideas to extend SynthGuard into a more powerful and practical system:

### ✨ Generation Quality
- Use **video-specific diffusion models** like [ModelScope T2V](https://huggingface.co/damo-vilab/modelscope-text-to-video-synthesis)
- Implement **frame interpolation** for smoother motion using RIFE or DAIN

### 🧠 Prompt Intelligence
- Add **prompt enrichment** using GPT to expand vague user inputs into rich scene descriptions
- Support **multi-step prompts** to evolve scenarios frame by frame

### 📊 Anomaly Simulation
- Load a **base scene** and overlay anomalies (e.g. fire, smoke, intrusion)
- Train/fine-tune on industrial or surveillance datasets (synthetic + real)

### 🎛️ UI/UX Enhancements
- Full-featured **Streamlit Cloud deployment**
- Add sliders for number of frames, seed, resolution, etc.
- Include **video gallery** for recent generations

### 🌐 Deployment
- Package into a web app or API (FastAPI or Flask backend)
- Deploy via Docker, Hugging Face Spaces, or Streamlit Cloud

## 🧑‍💻 Authors

- Built by [Me](https://www.github.com/DivyanshuVashisht)
- Powered by [🤗 Hugging Face](https://huggingface.co/), `diffusers`, and open-source tools

---

## 📜 License

MIT License – use freely and adapt with credit.