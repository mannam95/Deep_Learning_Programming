# Assignment 10 - Adversarial Examples

## Submission Details

- Implemented Adverserial training on Fashion-MNIST
- Variation1: Creating Adversarial Examples (Only for testing)
  - Trained a model on Fashion-MNIST dataset.
  - For the test dataset created adverserial examples by wrapping in GradientTape and created adverserial examples.
    - Adverserial_Bathc = current_Image_Batch + (0.003 \* gradient)
  - For the main test data the accuracy is 92%.
  - For the adverserial test data the model performed very poor which is 40%.
- Variation2: Train Model with Adverserial Data
  - To solve the above problem occured in variation-1, now trained a model with adverserial examples.
  - Created adverserial examples for the entire train dataset, so the data became double
  - Now trained the entire model.
  - Test accueacy achieved was 90%.
  - Adverserial examples here performed better and the accuracy improved to 70%.
- Further details related to the task can be found in the below task URL.
- Task URL : [https://ovgu-ailab.github.io/idl2021/ass10.html](https://ovgu-ailab.github.io/idl2021/ass10.html)
