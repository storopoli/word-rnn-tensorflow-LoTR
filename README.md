# word-rnn-tensorflow Lord of The Rings

Multi-layer Recurrent Neural Networks (LSTM, RNN) for word-level language models in Python using TensorFlow. 

The input data is all the 3 books of Tolkien's LoTR in a single *txt* file

Mostly reused code from https://github.com/sherjilozair/char-rnn-tensorflow which was inspired from Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn).


# Requirements
- [Tensorflow 1.1.0rc0](http://www.tensorflow.org)

# Basic Usage
To train with default parameters on the lotr corpus, run:
```bash
python train.py
```

To sample from a trained model
```bash
python sample.py
```

# Sample output

### Word-RNN
```text
His face passed over him. 'What do you know already?'

'Perhaps,' said Éomer. 'For Boromir had one else many tales nor friendhip would grow over the fields of the noble Riders?' 

'Yes,' said Sam, sitting upward aside with a voice. 'Could I was to tell the truth, I deemed them my plan before you ask out of these days. Some dwarf-gates can't see.'

There was another stern a image of mark in the shadows of Isengard would creep the trail of the Moon, Aragorn went to the door, like a banner, silent and on deep sunlight came out to Tol heart; for the one on loomed up a vision of his helm and sat silent in the plain shadows of Faramir’s helm was left clean slopes, and the out-wall sky was empty and like a light of Huorns had already carried out a long sloping land. 

There was a long fold of the East away beyond the north the gates and clustered tall and fell; shaped chill upon the open sun. Now the mighty grey left stands rode, wriggling silent. After Sam was moving apart from his shoulders. Tonight he was named or gloomy up either they came, and stabbed mostly as they could.
```
