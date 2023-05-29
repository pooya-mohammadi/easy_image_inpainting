# Easy Image Inpainting

In this repository, we provide a simple interface for editing images using the Generative AI.
We have several sections for this process:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pooya-mohammadi/easy_image_editing/blob/main/easy_image_editing_grounding_dino_glide.ipynb)

## Object Selection:

In this section, we choose the object we want to edit. To do this we use Grounding Dino model. A sample:</br>
**Input Image:</br>**
<img src="https://github.com/pooya-mohammadi/deep_utils/releases/download/1.0.2/golsa_in_garden.jpg" width="400">

**Text for object selection: `Hen`</br>**
**Output Image:</br>**
<img src="https://github.com/pooya-mohammadi/deep_utils/releases/download/1.0.2/golsa_in_garden_dino.png" width="400">

### TODO List:

- [x] Add Grounding Dino model

## Image Inpainting:

In this section, we replace the selected objects with generated images. A sample:</br>

Text for object generation: `Dead leaves`</br>

As you can see, the `hen` is replaced with `dead leaves`.</br>

**Output Image:**</br>

<img src="https://github.com/pooya-mohammadi/deep_utils/releases/download/1.0.2/glide_output.jpg" width="400">

### TODO List:

- [x] Add GLIDE model
- [ ] Add Diffusion models

# References:

1. https://github.com/IDEA-Research/GroundingDINO
2. https://github.com/openai/glide-text2im
3. https://github.com/pooya-mohammadi/deep_utils
