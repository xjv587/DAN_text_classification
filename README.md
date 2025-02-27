# DAN for Text Classification with Robust Word Embeddings
This project focuses on training feedforward neural networks in PyTorch for sentiment classification. The key innovation lies in leveraging pretrained word embeddings (GloVe) while experimenting with various architectures and optimization techniques. The work includes:

  - Neural Network Optimization: Implemented and tuned stochastic gradient descent (SGD) for a mathematical optimization problem.
  - Deep Averaging Network (DAN): Built a text classification model by averaging word vectors and passing them through a feedforward neural network. Experimented with different hidden layer sizes, activation functions, dropout layers, and optimizers (Adam, SGD).
  - Batching and Efficiency: Enhanced model efficiency by implementing batch processing, handling variable-length sequences with padding, and fine-tuning hyperparameters to optimize training speed and accuracy.
  - Robustness to Misspellings: Designed a typo-resilient NLP model by implementing:
    - Prefix embeddings: Generalizing word vectors by focusing only on the first three characters, mitigating out-of-vocabulary (OOV) issues.
    - Spelling correction with edit distance: Using NLTK-based Levenshtein distance to match misspelled words to known vocabulary terms.

# Key Achievements:
✅ Achieved 79% accuracy on sentiment classification.

✅ Implemented word embedding techniques to enhance generalization.

✅ Built typo-resistant models, improving accuracy on noisy text to 75%.

✅ Optimized training to complete in under 10 minutes.
