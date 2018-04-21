# Generate PAE Edesaikos Text

Aka 'Thomas Matsios' text.

## Install python dependencies

1. Run ``pip install tensorflow``
2. Run ``pip install numpy``

## Train the network

Run the following command in order to train the network:

``python rnn_tf.py --input_file=data/matsios.txt --ckpt_file="saved/model.ckpt" --mode=train``

## Run the network to generate text

``python rnn_tf.py --input_file=data/shakespeare.txt --ckpt_file="saved/model.ckpt" --mode=talk``
