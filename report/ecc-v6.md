# Bidirectional LSTM-RNN vs. Basic LSTM-RNN Convergence Rate

Fixed: `n = 25000, rate = 0.5, p = 0.5, l = 3`

error = 0.05

### K10

**Basic LSTM**

![basic-k10-e0.05](img/v6/basic-k10-e0.05.png)

Viterbi Decoding Loss: 0.0059

**Bidirectional LSTM**

![bidir-k10-e0.05](img/v6/bidir-k10-e0.05.png)

Viterbi Decoding Loss: 0.0059

### K20

**Basic LSTM**

![basic-k20-e0.05](img/v6/basic-k20-e0.05.png)

Viterbi Decoding Loss: 0.0075

**Bidirectional LSTM**

![bidir-k20-e0.05](img/v6/bidir-k20-e0.05.png)

Viterbi Decoding Loss: 0.0075

### K40

**Basic LSTM**

**![basic-k40-e0.05](img/v6/basic-k40-e0.05.png)**

![lstm-rnn-k40-e0.05-train](img/v6/lstm-rnn-k40-e0.05-train.png)

Viterbi Decoding Loss: 0.0082

**Bidirectional LSTM**

![bidir-k40-e0.05](img/v6/bidir-k40-e0.05.png)

Viterbi Decoding Loss: 0.0082

# Bidirectional LSTM-RNN on High Error Rate

Fixed: `n = 25000, rate = 0.5, p = 0.5, l = 3`

error = 0.15

### K10

**Basic LSTM**

![lstm-rnn-k10-e0.15-train](img/v6/lstm-rnn-k10-e0.15-train.png)

Final Test Accuracy after 50+ epoches: 92.4%

Viterbi Decoding Accuracy: 93.7%

**Bidirectional LSTM**

![bidir-k10-e0.15](img/v6/bidir-k10-e0.15.png)

Final Test Accuracy after 20 epoches: 90.3%

Viterbi Decoding Accuracy: 93.7%

### K20

**Basic LSTM**

![lstm-rnn-k20-e0.15-train](img/v6/lstm-rnn-k20-e0.15-train.png)

Final Test Accuracy after 80+ epoches: 88.7%

Viterbi Decoding Accuracy: 91.9%

**Bidirectional LSTM**

![bidir-k20-e0.15](img/v6/bidir-k20-e0.15.png)

Final Test Accuracy after 20 epoches: 83.3%

Viterbi Decoding Accuracy: 91.9%


### Normalization of Training Data

**basic-normalization-train**

![basic-normalization-train](img/v6/basic-normalization-train.png)

Viterbi Decoding Loss: 0.0059

**basic-normalization-val**

![basic-normalization-val](img/v6/basic-normalization-val.png)

Viterbi Decoding Loss: 0.0059

