# style_transfer_van_gogh


This Pipeline builds on Zhu et al.'s work (2017) for unpaired image-to-image translation, to apply Van Gogh's painting style to nature and landscape photographs I have captured over the last three years. The task leverages **CycleGAN**’s ability to handle unpaired datasets, which makes it particularly suitable for this application where the images from the two domains (photographs and paintings) are visually related but not perfectly matched. 

In This pipeline, I extend the application of CycleGAN through **Hyperparameter Tuning** by running multiple Sweeps on the **WandB** website. I further apply **Inversion-Based Style Transfer by Fine Tuning a Stable Diffusion Model** building on the research conducted by Zhang et al. (2023). 


I have deployed the model on HuggingFace Spaces and Utilized Gradio.io to create a simple UI. You can try the model here by uploading a landscape or nature image and the results should be Van Gogh Styled (based on the model performance so far). [Here](https://huggingface.co/spaces/rwankhalifa/van_gogh) is the link for the deployed model.

Review this Documentation for full Pipeline Analysis:
[Pipeline Documentation & Analysis](https://drive.google.com/file/d/1ywMaRQE83ObeH3fR2anB667cS7RuNgvE/view?usp=sharing)
