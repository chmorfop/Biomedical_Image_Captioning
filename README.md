# Biomedical_Image_Captioning

In the last years, the deep learning task of Image captioning was very challenging. Image
captioning is a combination of Computer Vision and Natural Language Processing, which are
the two 2 sub main areas of deep learning. Essentially, Image captioning is an end-to end
sequence to sequence embedding task where, image pixels are input sequences and captions are
describing the images as a desired output. In this way, with respect to an image, a model can
generate an output as a label or caption. The process of image captioning is very useful in many
sections nowadays, especially in the medical sections where a model can briefly describe in
few words the condition of a patient. However, the implementations of Image captioning, with
older architectures such as Convolutional Neural Networks and LSTMs or RNN, had a very
low performance mainly due to the limitations of the LSTM architecture. The attention
mechanism along with the Transformer architecture which was introduced in “Attention Is All
You Need” paper had great impact both in NLP with Language Models such as Bert and in
Computer Vision with image recognition models such as ViT. In this way, applying these new
architectures in the image captioning task can improve the overall performance of the models.
In this paper, we will explore not only the old but also the new architectures of Image captioning
and monitor the performance of the respective models.

**Training Models**:
* ***DenseNet & LSTM***
* ***ViT & Roberta***
* ***ViT & GPT2***
* ***ViT & BioBert***




**Model Performance**:
As we can notice from the bar chart, the encoder-decoder
model of ViT & Bio Bert scored the greatest Rouge-1 F1 metric with 31%.
With respect to the evaluation metrics and
the overall performance of the models, we noticed that the encoder-decoder models are
more robust to image captioning task, outperforming the older architecture models ( CNN & LSTM)

**Results**:
![Example Image](images/T5_model_variants.png)
