# TensorFlow Dynamic RNN

An LSTM classifier trained on generated variable-length sequences. It distinguishes increasing linear sequences from random sequences and uses masking to ignore padded timesteps.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python dynamic_rnn.py
```

The toy dataset is generated in memory; training runs for 2,000 steps and reports loss and accuracy.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/).