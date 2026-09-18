# RNNoise real-time filter

Desktop mic filter. PyQt window with a live waveform, enable/disable, input gain, and output volume. Audio is denoised with RNNoise at 48 kHz.

## What is in here

- `main_gui.py` / `main.py` — Qt UI and PortAudio callback
- RNNoise / pyrnnoise processing
- Start/stop stream controls

## Stack

Python, PyQt5, sounddevice, RNNoise
