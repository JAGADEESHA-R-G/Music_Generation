# char-rnn-keras

Multi-layer recurrent neural networks for training and sampling from texts, inspired by [karpathy/char-rnn](https://github.com/karpathy/char-rnn).

### Requirements

This code is written in Python 3, and it requires the [Keras](https://keras.io) deep learning library.

### Usage

All input data is placed in `data/` directory.`input.txt` is taken from  [Nottingham Dataset](https://github.com/jukedeck/nottingham-dataset).

To train the model with default settings:
```bash
$ python train.py
```

To sample the model:
```bash
$ python sample.py
```

after running copy the notes generated and paste in https://www.abcjs.net/abcjs-editor.html to hear.


Training loss/accuracy is stored in `logs/training_log.csv`.
