# ocr_mnist_detect
---
## Notebook-1: OCR_customCNN: <br>
The notebook contains the main model training code, <br>
Two approaches have been adopted <br>
a. First a pretrained model `convnext_tiny` model has been finetuned for `10 epochs` on a `base learning rate of 0.0025` <br>
b. Second a custom model is created `MNISTNet` that has been trained for `8 epochs` on a base learning rate of `0.025`.

Metrics of the model: <br>
*ConvNeXT model*: 98.9% accuracy.<br>
*MNISTNet*: 99.1% accuracy.
---
## Notebook-2: Gradio app:
I have added a custom demo application to demonstrate the working of the models.
