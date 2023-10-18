# Tackling Wav2vec 2.0  

Here's the table of contents fro easy access:

1. TOC
{:toc}

## Mini introduction to wav2vec
Using accurate AI jargon Wav2Vec is a novel framework for self-supervised learning of representations from raw audio data. This approach is based on the Transformer's encoder, Convolutional Neural Networks (CNN) and masked language modeling techniques. 

In my attempt to make it simple, is a CNN that takes in a batch of raw audio and is able to obtain a general representation of it to apply to another, more complicated, speech related task (e.g speech recognition). 

## What goes into pre-training?

## How can we modify the model? 

## Helpful resources 
I have found very illustrative (obviously) blog that breaks down the essential components that make Wav2Vec stand out. [An Illusatrated Tour of Wav2vec 2.0](https://jonathanbgn.com/2021/09/30/illustrated-wav2vec-2.html) by Jonathan Bgn

[Self-training and pre-training, understanding the wav2vec series](https://maelfabien.github.io/machinelearning/wav2vec/#) by Maël Fabien

[A quick review of "Wav2Vec: unsupervised pre-training for speech recognition" paper](https://medium.com/@amirhossein.abaskohi/a-quick-review-of-wav2vec-unsupervised-pre-training-for-speech-recognition-paper-320dfac2fc3a) by Amirhossein Abaskohi

[Original paper](https://proceedings.neurips.cc/paper/2020/hash/92d1e1eb1cd6f9fba3227870bb6d7f07-Abstract.html)

Helpful code implementations can be found in [Hugging Face Wav2Vec implementation](https://huggingface.co/docs/transformers/model_doc/wav2vec2#transformers.Wav2Vec2ForPreTraining)
