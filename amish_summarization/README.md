# tensorflow-text-summarization



Encoder-Decoder model with attention mechanism.Used LSTM cell with [stack_bidirectional_dynamic_rnn](https://www.tensorflow.org/api_docs/python/tf/contrib/rnn/stack_bidirectional_dynamic_rnn).
Used LSTM [BasicDecoder](https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/BasicDecoder) for training, and [BeamSearchDecoder](https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/BeamSearchDecoder) for inference
Used [BahdanauAttention](https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq/BahdanauAttention) with weight normalization.

## Requirements
- Python 3
- Tensorflow (>=1.8.0)
- pip install -r requirements.txt

