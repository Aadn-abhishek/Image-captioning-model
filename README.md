## Image-captioning-model:
# Remote Sensing image captioning data (Rsicd) dataset - https://www.kaggle.com/datasets/thedevastator/rsicd-image-caption-dataset

## Building the model
Our image captioning architecture consists of three models:

- **A CNN: used to extract the image features**
- **A TransformerEncoder: The extracted image features are then passed to a Transformer based encoder that generates a new representation of the inputs**
- **A TransformerDecoder: This model takes the encoder output and the text data (sequences) as inputs and tries to learn to generate the caption.**
