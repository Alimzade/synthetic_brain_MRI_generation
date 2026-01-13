# Image Synthesis for Brain MRI Using DDPM and DCGAN

This repository advances medical imaging by implementing Denoising Diffusion Probabilistic Models (DDPM) and Deep Convolutional Generative Adversarial Networks (DCGAN) to generate high-fidelity synthetic Brain MRI images. It aims to enhance diagnostics and research, focusing on synthesis of images that closely resemble actual MRI scans.

<img width="624" height="533" alt="project_ddpm" src="https://github.com/user-attachments/assets/e37851a3-5d17-4d4c-9e8a-45b44303b98e" />


### Technologies:

- **DDPM:** Models the distribution of real images and gradually converts noise into structured data through a reverse diffusion process.
- **DCGAN:** Employs a generative adversarial network architecture optimized for deep convolutional networks.

To install necessary libraries for DDPM, you should first run:
```
pip install monai-generative
```

### Evaluation Metrics

- **Fréchet Inception Distance (FID):** Lower scores indicate higher similarity to real images.
- **Inception Score (IS):** Higher scores reflect greater detail and diversity.
- **Kernel Inception Distance (KID):** Lower scores suggest better model performance.

### License

This project is released under the **MIT License**, promoting open access for academic and research purposes. The goal is to encourage collaboration and the sharing of advancements in medical image synthesis, fostering an environment of innovation and growth in the field.
