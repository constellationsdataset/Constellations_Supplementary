# Constellations_Supplementary
Contains generation code and samples from dataset 

We explain below the folders in the repository:

### Dataset Samples
We show in here a very small subset of our dataset, which was
part of the set used in the human experiments. The link to full dataset will be added later.

---
### Code (Constellations_pipeline-main)
Code used to generate the constellation images, including a demo notebook offline
version (using a downloadable pre-trained Mask-RCNN) and online version by
uploading and running on colab (Colab Demo.ipynb)


---
### (Constellations_pipeline-main\Data_position_evaluate)
This folder contains a few functions we use to get the position of dots in the dotted and
constellation version of the image. One can also use these tools to check how many
dots, a sketch drawn on this image passes through. Demo of usage of these functions
are in ‘Position and evaluation demo.ipynb’


---
### (Constellations_pipeline-main\Evualuate_CLIP)
This folder contains two notebooks used to evaluate the classification performance of 4 CLIP models agains the modalaties in our Dataset.
The notebook 'sort_modalities.ipynb' constains helper script to sort images from main dataset folder, modality wise (for which link will be provided later). 'CLIP_Evaluation.ipynb' is the main scipt that evaluates the CLIP model on the dataset and plots Figure 4 from the manuscipt. 

Please follow CLIP usage instructions on https://github.com/openai/CLIP to install the correct environment, before using the scripts.
