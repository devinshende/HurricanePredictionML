# Hurricane Satellite Imagery Damage Detection
Fork of repository Deep Learning Based Damage Detection on Post-Hurricane Satellite Imagery
We added additional data to try and improve detection from kaggle competition

* The dataset: 
  1. train_another     : the training data; 5000 images of each class
  2. validation_another: the validation data; 1000 images of each class
  3. test_another      : the unbalanced test data; 8000/1000 images of damaged/undamaged classes
  4. test              : the balanced test data; 1000 images of each class

Notebooks:
 * exploration.ipynb - has some initial charts and data exploration steps. This was the first thing we did
 * resnet50.ipynb - trying out the pretrained resnet model and retraining to our dataset with 50 epochs from hugging face
 * CNN.ipynb - modified from research paper very slightly, this introduces a basic CNN model with keras
 * vit.ipynb - trying to use a pretrained ViT model from HuggingFace and adapting to our dataset.
 * newResnet.ipynb - some changes to the 50 epochs resnet model
