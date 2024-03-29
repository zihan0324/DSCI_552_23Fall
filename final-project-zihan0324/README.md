**Data set can be downloaded through:**

https://www.dropbox.com/sh/38zygdpo6u7alwy/AAB1PJuhqF-58GZJ-oD4xl5Ya?e=1&dl=0

(Data is not uploaded because of size)

# [Notebooks](./notebooks/)

Notebooks containing data processing, model training, and model evaluation.

1. [CNN + MLP](./notebooks/cnnMLP.ipynb)

2. [EfficientNetB0](./notebooks/transferLearning_EB.ipynb)

3. [ResNet](./notebooks/transferLearning_ResNet.ipynb)

4. [VGG16](./notebooks/transferLearning_VGG.ipynb)


# [Models](./models/)

Models with minimum validation loss, which can be applied to replicate model results with ```model.load_weights``` (for '.hdf5' files) or ```keras.models.load_model``` (for '.h5' & '.keras' files)

1. [CNN + MLP](./models/best_mlp_model.h5)

2. [EfficientNetB0](./models/best_eb_mode.keras)

3. [ResNet](./models/best_rn_model.keras)

4. [VGG16](./models/best_vgg_model.keras)

