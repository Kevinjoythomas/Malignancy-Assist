# Malignancy-Assist
### Description 🌟
In this breast cancer detection project, I embarked on a journey to design predictive models leveraging diverse techniques to differentiate between malignant and benign cells. The primary aim was to contribute to breast cancer prevention through accurate identification.

### Goal 🎯

The main goal was to construct a model capable of distinguishing between cancerous (malignant) and non-harmful (benign) breast cells. I used two different methods: one that's a technique in math called logistic regression, and another that's more like how our brains work, called a deep learning neural network. Both were aimed at making sure these programs were very good at spotting the dangerous cells early on. This could help doctors find potential problems sooner and take steps to stop breast cancer from developing.

### Models Implemented 🧠

Logistic Regression: Built entirely from scratch✨, without using any imported modules from sklearn or TensorFlow but using NumPy arrays and vectorization. It featured a custom-defined sigmoid function and log loss calculation. Employing gradient descent and incorporating min-max scaling, this model achieved an impressive 97.36% accuracy on the test dataset.

Deep Learning Neural Network: Constructed using Keras, the neural network architecture comprised:

Input Layer: 30 neurons, employing the sigmoid activation function.

Hidden Layers: Consisting of 100 neurons with tanh activation, 200 neurons with ReLU activation, and an additional 100 neurons with ReLU activation.

Output Layer: A single neuron using sigmoid activation.

This model was optimized using the Adam optimizer and binary cross-entropy loss function across 10 epochs, trained on a batch size of 32.

Achieved an accuracy of 96.49% on the testing set.

