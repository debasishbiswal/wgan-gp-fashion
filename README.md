#  WGAN-GP on Fashion-MNIST

A from-scratch PyTorch implementation of Wasserstein GAN with Gradient Penalty (WGAN-GP), trained on Fashion-MNIST.

This project was built and tested using **Paperspace Gradient Notebooks**, but you can run it locally or on Colab too. It includes fully documented code, visual outputs, and lessons from training GANs the hard way.

---

##  Background

This repo supports my Medium article:  
 [**GANs Love to Cheat — WGAN-GP Taught Mine Discipline**](https://medium.com/@debasishbiswal04/gans-love-to-cheat-wgan-gp-taught-mine-discipline-c2b2db3ac7fa)

It’s the follow-up to:  
 [**I Built a GAN That Draws Clothes**](https://medium.com/@debasishbiswal04/i-built-a-gan-that-draws-clothes-and-heres-everything-i-learned-3900c35dfd94)

---

## Features

-  Implements WGAN-GP from scratch using PyTorch
-  Trains on Fashion-MNIST for 200 epochs
-  Includes critic + generator training loops with gradient penalty
-  Plots generator and critic losses over time
-  Visualizes outputs every `display_step`

---

## How to Run

### Run on Paperspace
1. Go to [https://paperspace.com/gradient](https://paperspace.com/gradient)
2. Start a new **Jupyter Notebook** and upload `wgan_gp_fashion.py`
3. Enable GPU via the Notebook settings (Runtime type → GPU)
4. Run the cells step-by-step



