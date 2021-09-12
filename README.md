With cutting edge research implementations, thousands of trained models easily accessible, the Hugging Face transformers library has become critical to the success and growth of natural language processing today.

For any machine learning model to achieve good performance, users often need to implement some form of parameter tuning. Yet, nearly everyone (1, 2) either ends up disregarding hyperparameter tuning or opting to do a simplistic grid search with a small search space.


If you’re leveraging Transformers, you’ll want to have a way to easily access powerful hyperparameter tuning solutions without giving up the customizability of the Transformers framework.
![image](https://user-images.githubusercontent.com/17935007/133003874-0c331062-3edd-4ad4-a4cb-6b7b0291237e.png)

In the Transformers 3.1 release, Hugging Face Transformers and Ray Tune teamed up to provide a simple yet powerful integration. Ray Tune is a popular Python library for hyperparameter tuning that provides many state-of-the-art algorithms out of the box, along with integrations with the best-of-class tooling, such as Weights and Biases and tensorboard.

To demonstrate this new Hugging Face + Ray Tune integration, we leverage the Hugging Face Datasets library to fine tune BERT on MRPC.


