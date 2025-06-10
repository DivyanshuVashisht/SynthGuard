# 🛡️ SynthGuard – Generative AI for Anomalous Event Simulation

SynthGuard is a lightweight prototype that simulates rare or unusual events as short videos based on text prompts.

## 🚀 Features

- Text-to-video generation using Stable Diffusion
- Generates 5–10 frame sequences
- View output instantly in a Streamlit dashboard

## 🧰 Stack

- Python
- Stable Diffusion via `diffusers`
- `ffmpeg-python`
- Streamlit

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/SynthGuard.git
cd SynthGuard
pip install -r requirements.txt
streamlit run src/ui.py