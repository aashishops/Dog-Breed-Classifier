
# Dog Breed Classifier

The Dog Breed Classifier with VGG16 is an image classification project that identifies the breed of a dog based on input images. The model is trained using the VGG16 architecture and a dataset from Stanford University containing a wide variety of dog breeds.

#Key Features
- Precise Classification: The classifier can accurately with an accuracy 99%. It identify over 120 different dog breeds, making it a powerful tool for dog enthusiasts and researchers.

- VGG16 Architecture: The model is built on the VGG16 deep learning architecture, known for its effectiveness in image classification tasks.

## How it works
The Dog Breed Classifier employs the following steps:

- Data Preparation: The Stanford Dog Dataset, consisting of thousands of labeled dog images, is preprocessed and divided into training, validation, and test sets.

- Transfer Learning: The VGG16 model, pre-trained on the ImageNet dataset, serves as the base model. Only the top layers are customized for the specific dog breed classification task.
![arci](https://raw.githubusercontent.com/aashishops/Dog-Breed-Classifier/main/images/architecture.png)
 - Training: The model is fine-tuned using the training set to adapt it to the nuances of dog breed recognition. The training process involves multiple epochs and utilizes techniques like data augmentation.

 - Validation: The model's performance is assessed on the validation set, helping to prevent overfitting and fine-tuning hyperparameters.

- Testing: The final model's accuracy and reliability are evaluated on the test set.

![test](https://raw.githubusercontent.com/aashishops/Dog-Breed-Classifier/main/images/image2.png)
## Run Locally

Clone the project

```bash
  git clone https://github.com/aashishops/Dog-Breed-Classifier
```

Go to the project directory

```bash
  cd Dog-Breed-Classifier
```

Install Prerequisite

```bash
  pip install -r requirements.txt
```


