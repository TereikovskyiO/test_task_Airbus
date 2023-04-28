# test_task_Airbus
This repo is the test task execution. The task is to create notebooks for segmentation of images from Kaggle Airbus Ship Detection Challenge using Unet neural model.
There are two Colab files: data-analysis-unet-dwt-tenserflow.ipynb - for the training of Unet model on the dataset; test_unet_ships.ipynb - for the ship segmentation of the input image.
In the former Colab file the custom Unet model was created and it was trained on the part of the dataset. For loss evaluation Dice function was used.
