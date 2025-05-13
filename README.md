# GenAI-Video-Synthesis-Realistic-Talking-Avatars
# 🌐 Multilingual Lip-Synced Video Generator with AI + Whisper + GFPGAN + Wav2Lip

"GenAI Video Synthesis: Realistic Talking Avatars from Text Prompts" This project uses Generative AI to turn a simple text prompt into a realistic talking video. It starts by taking input from the user and generating a natural, human-like response using AI Large language model. That text is then converted into speech using gTTS, and the audio is adjusted to match the length of a chosen video clip. The real magic happens with Wav2Lip, a deep learning model that analyzes the person’s face in the video and syncs their lip movements to the generated speech, making it look like they’re actually saying the words. To improve video quality, I also integrated GFPGAN, which can clean up and enhance the face if the original video is low-resolution. This project brings together multiple Gen AI tools—text generation, text-to-speech, and video synthesis—to create seamless, AI-driven video content. It’s a great example of how these technologies can be combined to build useful applications like virtual presenters, AI avatars, or automated dubbing tools.

This project is an end-to-end pipeline that transforms text prompts into high-quality, lip-synced videos with realistic speech and enhanced facial visuals. It leverages a combination of generative AI, speech models (Whisper, XTTS, gTTS), and video processing tools (Wav2Lip, GFPGAN) to:

---

## 🚀 Features

✅ Generate spoken content from a text prompt

✅ Translate and voice-over in multiple languages

✅ Sync speech to any face in a video realistically

✅ Improve facial quality frame-by-frame

✅ Export a clean, polished video with synced audio

---

🧠 Pipeline Overview

📥 Upload video through interactive widget

💬 Generate text using AI

🗣️ Convert text to audio with gTTS

🎧 Speech transcription using Whisper

🌐 Translate text to selected language

🔊 Regenerate voice using XTTS (multilingual)

👄 Lip-sync voice with video using Wav2Lip

🖼️ Enhance frames using GFPGAN

🎞️ Recompile enhanced video

📤 Download final video with synced audio

---

Install Dependencies

!apt-get install -y ffmpeg libsm6 libxext6,
!pip install numpy==1.23.5,
!pip install TTS gtts googletrans==4.0.0-rc1,
!pip install git+https://github.com/openai/whisper.git,
!pip install --upgrade torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118,
!pip install --upgrade torchao

---

📌 Requirements:

Python 3.8+

PyTorch with CUDA (recommended for performance)

Google Colab (for easy GPU access and interactive flow)

FFmpeg

OpenCV

---

🧪 Demo Instructions
Run the notebook in Google Colab.

Upload a video file via the widget.

Enter a prompt to generate text via AI.

Follow through the cells to generate a final enhanced video.

Final result will be available for download.

---

Acknowledgements:
Thanks to the original creators of:

Wav2Lip

GFPGAN

Whisper

Google Gemini

Coqui TTS
