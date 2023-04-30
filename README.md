# Sequence to Sequence English to IPA Phonetics Model

A Sequence to Sequence (Seq2Seq) English to International Phonetic Alphabet (IPA) Phonetics model, created with TensorFlow, serves as a proof of concept for transforming conventional written English text into its corresponding IPA phonetic representation. The ultimate objective of this machine learning project is to facilitate the generation of IPA phonetics dictionaries for an array of languages and dialects. 

The Seq2Seq framework encompasses two fundamental constituents: an encoder network and a decoder network.

1. Encoder Network: The primary function of the encoder is to process input data in the form of written English sentences or phrases. By tokenising each word or character into numerical sequences, it creates a stable internal context vector that captures essential information about the input sequence. This high-dimensional representation retains meaning while allowing effective identification of patterns within the data.

2. Decoder Network: Working with the internal context vector created by the encoder, the decoder's objective is to produce accurate IPA transcriptions using the knowledge gained during training phases. Language modelling techniques like Attention Mechanism further enhance performance by guiding decoders towards critical parts of source texts during translation processes.

Training this Seq2Seq model requires a large dataset containing pairs of aligned words and their respective IPA transcriptions; this way, patterns are identified concerning spelling variations that dictate pronunciation rules which eventually contribute to more precise translations between textual data points.
