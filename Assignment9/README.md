# Assignment 9 - Auto Encoders
## Submission Details
* Implemented Self-Supervised Learning on Fashion-MNIST
* Labels are not used during Auto Encoders training. The labels are the inputs itself.
* Variation1: MLP - Classification (Image Compression)
    * Implemented an encoder, decoder with MLP and trained the Auto Encoder.
    * Extracted Encoder model from the trained AutoEncoder. 
    * Freezed the Encoder trainable params.
    * Added additional dense layers and built a classification model.
    * Taken a subset of data which is 1000 items and trained the classification model (Encoder layers are just being used as we freezed the trainable params).
* Variation2: CNN (Added Noise)
    * Trained in a similar fashion like above, but now the inputs have an additional noise and now the layers are convolution not dense layers.
* Further details related to the task can be found in the below task URL.
* Task URL : [https://ovgu-ailab.github.io/idl2021/ass9.html](https://ovgu-ailab.github.io/idl2021/ass9.html)