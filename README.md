# Exploring the Latent Space of StyleGAN
Bachelor's Thesis in Artificial Intelligence \
By Karlijn Bok

Original code by Dmitry Nikitko (Puzer): https://github.com/Puzer/stylegan-encoder, who used the implementation of the original StyleGAN paper 
> A Style-Based Generator Architecture for Generative Adversarial Networks
Tero Karras (NVIDIA), Samuli Laine (NVIDIA), Timo Aila (NVIDIA)
http://stylegan.xyz/paper


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
