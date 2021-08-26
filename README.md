# Deepfake-detection-project-for-CS523
Deepfake image detection project for CS523


Download dataset from: https://www.kaggle.com/xhlulu/140k-real-and-fake-faces

# How it works:

1. Save the dataset under the same directory as the jupyter notebook files. Under this dataset there should
   be 3 different dir named `train/`, `valid/`, and `test/`. If you don't want to make changes to the path 
   in the jupyter notebook file, you can name the dataset `140K-data/` and make sure the path to `train/`, 
   `valid/`, and `test/` is called `./140K-data/real_vs_fake/real-vs-fake/`.

2. You can uncomment the Save Module cell and run the notebooks to train and save modules. Modules are saved
   under `.h5` extension.

3. You can run cells below train with different modules to predict the model and get accuracy, results, and 
   plots.

>Pretrained model for Custom CNN is uploaded. Pretrained models for VGG16 and DenseNet are unable to be uploaded because they are too big. 
