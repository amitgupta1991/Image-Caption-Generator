# Image-Caption-Generator

Image Caption Generator for Visually Impaired People

## Objective

To generate an output which would describe in a sentence about what is being shown in the image – the object that is present, their properties and the action that is being performed and the interaction between the objects etc.

## Steps Performed

1. A combination of CNN and RNN were used.

2. CNN acts as a encoder to extract features from the images and RNN acts as a decoder to generate relevant captions. LSTM was the type of RNN used.

3. In order to predict the captions for the images, the model was trained using LSTM.  The data was trained using Flickr8k dataset.

4. After training, the machine now has some knowledge and based on that knowledge the LSTM model captions the images automatically.

5. When a new image is given to the LSTM model, it recalls the memory which has already been stored in the layers and based on that memory and the logic, it gives a caption to the image.

