# Lyric Creation based on Recurrent Neural Network
- Used one-hot encoding to represent word and use lyrics created by Jay Chou as dataset.
- Built Recurrent Neural Network model, use SoftmaxCrossEntropy as loss function, and use Per-
plexity to evaluate the model, which achieve lyric creation.
- Used gradient clipping to stablize training and prevent gradient explosion.