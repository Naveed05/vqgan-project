🚀 VQGAN + Transformer (Taming Transformers) — Image Generation Project

A complete implementation of VQGAN (Vector-Quantized Generative Adversarial Network) and Transformer-based autoregressive image generation, inspired by the Taming Transformers for High-Resolution Image Synthesis research paper by CompVis.
This repository provides the full architecture, configs, training scripts, and sampling pipelines required to:
Train your own VQGAN encoder–decoder
Use pretrained VQGAN checkpoints
Train a Transformer to generate discrete image tokens
Generate new high-quality images from learned codebooks

🧠 What This Project Contains
✔️ Full VQGAN architecture (encoder, decoder, quantizer, discriminator)
✔️ Transformer model for autoregressive code prediction
✔️ All training scripts from the official research repo
✔️ Complete configs for ImageNet, COCO, FaceHQ, ADE20K, etc.
✔️ Modular folder structure (easy to extend/customize)
✔️ Environment + requirements files
✔️ Ready for integration with custom datasets

📁 Project Structure
│
├── assets/               # For storing checkpoints, logs, datasets
├── configs/              # YAML configs for VQGAN + Transformer
├── data/                 # Dataset utilities
├── scripts/              # Sampling, training, utilities
├── taming/               # Core VQGAN + Transformer architecture
│   ├── data/
│   ├── models/
│   ├── modules/
│   └── *.py
│
├── environment.yaml      # Conda environment (PyTorch + dependencies)
├── requirements.txt      # Pip requirements
├── main.py               # Entry point for training
├── README.md
└── .gitkeep

📦 Pretrained Models (Not Included)
To run image generation or test sampling, download pretrained weights such as:
Model	Description
VQGAN ImageNet F16 16384	General-purpose image synthesis
COCO Transformer	Scene-based generation
FaceHQ VQGAN	High-resolution face generation

🤝 Contributions
This project is a research and learning implementation.
Feel free to fork, modify, improve architecture, or add new sampling approaches!

⭐ Support
If you find this useful, please ⭐ star the repo on GitHub!
More improvements and tutorials will be added soon.

