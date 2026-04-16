Fine-tuning Facebook's Wav2Vec2 transformer model for 
speech emotion recognition — bridging vision transformer 
experience to the audio domain.

# Goal
Apply transformer architecture knowledge (from ViT/CNN 
thesis work) to speech signals using a pretrained 
self-supervised audio model.

# Approach
Pretrained Wav2Vec2 → Fine-tune on RAVDESS 
→ 8-class emotion classification
→ Evaluate per-class precision/recall

# Tech Stack
Python · PyTorch · HuggingFace Transformers · Librosa

# Key Concepts
- Self-supervised speech representations
- Transfer learning on audio transformers
- Emotion classification from raw waveforms
- Fine-tuning strategy for small datasets

# Dataset
RAVDESS — 24 actors, 8 emotions, ~7,000 audio files

# Status
🔄 In Progress — April 2026
