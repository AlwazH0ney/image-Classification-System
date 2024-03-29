# Epoch
One complete pass through entire training dataset.
Epoch has two main numbers
- Loss and accuracy for training set (loss and accuracy)
- Loss and accuracy for validation set (val_loss and val_accuracy)
## Loss
Loss measures how well the model is doing for both training and validation sets.
**"_It is a number indicating how far the model's predictions are from actual labels_"**
### Note
Lower loss is better.
## Accuracy
Accuracy measures the percentage of correct predictions.
### Note
Higher accuracy is better.
# Important Info
- Epochs increase, training loss generally decreases and training accuracy increases indicating model is learning.
- Loss function values does not necessarily range from 0 to 1.
- Accuracy value do necessarily range from 0 to 1.
- e.g., 0.7 accuracy indicates 70% values have been predicted correctly.
# Confusion Matrix
<img width="791" alt="Screenshot 2024-01-10 at 12 10 35 AM" src="https://github.com/Nouman64-cat/Image-classification-Deep-Learning-/assets/112774247/0015a70a-3a80-456b-9242-909aeb1ad02c">

