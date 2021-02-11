# CMPM202P2
By Rebecca Lietz, Alison Crosby, Amelia Wang

Based on this repo: https://github.com/pbaylies/stylegan2-ada

We use a pretrained model to generate art from a WikiArt dataset. The above Github repo is the original base for this implementation, we simply created a Google Colab notebook to use the model.
The main method is generate_images_w_settings(), which allows the user to adjust variance, number of iterations, scale, and truncation during image generation. The generated image sets can then be joined into a grid using the createImageGrid() method. 

The original repo's Colab notebook had sliders and dropdown menus to modify those settings, but it was difficult to determine the effect each parameter had on the output, because a new image would be generated each time a value was changed. Our implementation allows the user to adjust the settings for 5 sets of images generated from the same input vector and observe the impact those different settings have.

How to use:
Open the notebook in Google Colab and run each cell, starting from the top.

![sample output](GANimages.png)
