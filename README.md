# Outfit_Swapping

## Overview
This is a implementation for text-prompt based outfit swapping for human avatar images, it consists of two components: (1) a text prompt-based segmentation model ([ClipSeg](https://github.com/timojl/clipseg)) that is used to extract mask corresponding to the dress region of the avatar image; (2) a text-guided inpainting model ([HD-Painter](https://github.com/Picsart-AI-Research/HD-Painter)) that is used to realistically inpaint the masked region of the avatar with user-specified outfit 

![workflow](https://github.com/user-attachments/assets/db2f26dd-ef61-4289-a2c8-bc83c64903cf)

## Data Preparationg and Preprocessing
The avatar images used in this implementation are from the 'Studio Avatar' tab in [link](https://app.heygen.com/avatars). And based on [heygen-generative-outfit-instruction](https://help.heygen.com/en/articles/8181925-heygen-generative-outfit-instructions) the images are cropped to close-up view, and individuals whose hair fall on the shoulder are not selected.

## Execution


