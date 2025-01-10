
---
title: CogVideoX-5B
emoji: 🎥
colorFrom: yellow
colorTo: blue
sdk: gradio
sdk_version: 4.44.0
suggested_hardware: l40sx1
suggested_storage: large
app_port: 7860
app_file: app.py
models:
  - THUDM/CogVideoX-5b-I2V
tags:
  - cogvideox
  - video-generation
  - thudm
short_description: Image-to-Video
disable_embedding: false
---

# Gradio Composite Demo

This Gradio demo integrates the CogVideoX-5B model, allowing you to perform video inference directly in your browser. It
supports features like UpScale, RIFE, and other functionalities.

## Local Run
### Installation
After cloning this repository, install the required packages:

```bash
pip install -r requirements.txt
```

### Running the code

```bash
python app.py
```
Then the app will be accessible at `0.0.0.0:7860`. If it is not accessible from your browser, change the ip in [this file](https://github.com/erfanasgari21/CogVideoX-5B-Space/blob/924868c8c2084df1bcf1f86edcb0ec8da97a502e/app.py#L491) to `127.0.0.1` to be accessible from `localhost`.



