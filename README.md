# Exploring the Latent Space of StyleGAN
Bachelor's Thesis in Artificial Intelligence \
By Karlijn Bok

Original code by Dmitry Nikitko (Puzer): https://github.com/Puzer/stylegan-encoder \
Who used the implementation of the original StyleGAN paper \
This repository contains (no longer) official TensorFlow implementation of the following paper:

A Style-Based Generator Architecture for Generative Adversarial Networks
Tero Karras (NVIDIA), Samuli Laine (NVIDIA), Timo Aila (NVIDIA)
http://stylegan.xyz/paper

Abstract: We propose an alternative generator architecture for generative adversarial networks, borrowing from style transfer literature. The new architecture leads to an automatically learned, unsupervised separation of high-level attributes (e.g., pose and identity when trained on human faces) and stochastic variation in the generated images (e.g., freckles, hair), and it enables intuitive, scale-specific control of the synthesis. The new generator improves the state-of-the-art in terms of traditional distribution quality metrics, leads to demonstrably better interpolation properties, and also better disentangles the latent factors of variation. To quantify interpolation quality and disentanglement, we propose two new, automated methods that are applicable to any generator architecture. Finally, we introduce a new, highly varied and high-quality dataset of human faces.

Two files were altered: 
* `align_images.py`
* `encode_images.py` was turned into `encode_images_ffhq.py` and `encode_images_clba.py`

Added folders/files:
* `enc_ffhq`
* `enc_clba`
* 

Original code was used to explore the latent space of two pre-trained versions of styleGAN, one trained on the FFHQ database, the other trained on the CelebA-HQ. Representations in latent space were found for 312 input images of the Radboud Faces Dataset (RaFD) [REF], after which the representation of identity (39 individuals), gender (20 male, 19 female) and emotion (angry, contemptuous, disgusted, fearful, happy, neutral, sad and surprised) was investigated.

Abstract: 
> ...
