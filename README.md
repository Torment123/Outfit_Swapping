# Outfit_Swapping

## Overview
This is a implementation for text-prompt based outfit swapping for human avatar images, it consists of two components: (1) a text prompt-based segmentation model ([ClipSeg](https://github.com/timojl/clipseg)) that is used to extract mask corresponding to the dress region of the avatar image; (2) a text-guided inpainting model ([HD-Painter](https://github.com/Picsart-AI-Research/HD-Painter)) that is used to realistically inpaint the masked region of the avatar with user-specified outfit 

