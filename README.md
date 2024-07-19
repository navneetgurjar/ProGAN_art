# ProGAN_art

Progressively Growing GAN model for Abstract image generation at a resolution of 256X256, 512x512.

1. The model is trained on a dataset of 6500 images of Art and pattern images.
2. Each Gnerator is trained for 30 epochs before going to the next resolution step.
3.  Trained folder contain optimally trained generators for specific resolution.

Use Saved_example file to generate images. The Generator takes input as a noise images (tensor), and then transforms it to meaning full image.

