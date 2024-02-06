# transferLearning-basics

This project is to classify the merch data available in MATLAB tutorials. Since the data is very limited (75 total images, 15 per class) using transfer learning becomes a obvious choice. The idea is to use pre-trained models (VGG19 and Inception V3) (previously trained on imagenet dataset). Since imagenet have a wide variety of object for image classification the model are already model to extraact the bbasic features from images like edgecs contoours etc. Now what we have to do is add our custom classifier on top of those pre-trained models, freeze the base layers and train the new classifier to fit our merch data.

### Results

- VGG19
<img width="457" alt="image" src="https://github.com/tusharparimi/transferLearning-basics/assets/93556280/02efbd51-ea31-4862-9914-20a44a9a0a21">

- Inception V3
<img width="476" alt="image" src="https://github.com/tusharparimi/transferLearning-basics/assets/93556280/c51aa125-59bb-43be-8c08-01b40a1525aa">


