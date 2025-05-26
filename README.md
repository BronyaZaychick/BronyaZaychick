- 👋 Hi, I’m BronyaZaychick
- 👀 I’m interested in deep learning, artificial intellegence, and video game!
- 🌱 I’m currently learning some knowledge about software engineering.
- 📫 If you have any questions, please send the email to wuyuelinerlin@outlook.com! 

#Code Description.
The code stored in is about a deep learning framework for multi-model fusion and data augmentation, serving to train and compare the performance differences between ResNet34, VGG16 and Vision Transformer (ViT) on the full dataset, a small sample (10%), and data augmentation conditions. All training models and test results are also placed in the code. The code for data augmentation is augmenting the train set and saving it as a new folder. The cuda12.8 used for the experiments was used for training.

The database used is Fish Dataset uploaded by Mark Daniel Lampa in kaggle at the link https://www.kaggle.com/datasets/markdaniellampa/fish-dataset/data.

#Instructions for use
Here in each piece of code can be run independently, no other plug-ins and model files, run the results will be saved in each independent folder, the specific path please see the code. Note that if there is a library that is not installed, please run the code after installation.

Cuda code can show the cuda version of the current training model, click to run.

Aug code is the code operation for data enhancement. There are various code enhancement methods in it, such as rotation, flipping, random masking and so on. The different combinations of enhancement methods used in the augmentation code are used to test the effect of different enhancement methods. Different enhancement results can be obtained by clicking run on each code. Each enhancement is saved in a separate folder.

The Resnet34, vgg16,vit code is used to train the model. Clicking run will train the model using the train set and test the model accuracy using the test set. All trained models are saved in a separate folder.

Resnet50 is the earliest test model that ended up not using the data in question, but the code works correctly and no other plugins are needed.

The Image code separately plots resnet34,vgg16,vit against different training results and saves the resulting images in a folder. Some of the code requires log files to run.
