## Introduction

Speech recognition is an interdisciplinary subfield of computer science
and computational linguistics that develops methodologies and technologies
that enable the recognition and translation of spoken language into text
by computers. It is also known as automatic speech recognition (ASR),
computer speech recognition or speech to text (STT). It incorporates
knowledge and research in the computer science, linguistics and computer
engineering fields.

This demonstration shows how to combine a 2D CNN, RNN and a Connectionist
Temporal Classification (CTC) loss to build an ASR. CTC is an algorithm
used to train deep neural networks in speech recognition, handwriting
recognition and other sequence problems. CTC is used when  we don’t know
how the input aligns with the output (how the characters in the transcript
align to the audio). The model we create is similar to
[DeepSpeech2](https://nvidia.github.io/OpenSeq2Seq/html/speech-recognition/deepspeech2.html).

We will use the LJSpeech dataset from the
[LibriVox](https://librivox.org/) project. It consists of short
audio clips of a single speaker reading passages from 7 non-fiction books.

We will evaluate the quality of the model using
[Word Error Rate (WER)](https://en.wikipedia.org/wiki/Word_error_rate).
WER is obtained by adding up
the substitutions, insertions, and deletions that occur in a sequence of
recognized words. Divide that number by the total number of words originally
spoken. The result is the WER. To get the WER score you need to install the
[jiwer](https://pypi.org/project/jiwer/) package. You can use the following command line:

## Images
![Screenshot 2023-08-03 012709](https://github.com/AnshulMaurya21/Automatic-Speech-Recognition-by-CTC/assets/87333511/12abe31c-8a72-4638-aff0-3faea0801284)

![Screenshot 2023-08-03 012832](https://github.com/AnshulMaurya21/Automatic-Speech-Recognition-by-CTC/assets/87333511/92c091f0-3a7d-45f7-916b-c4455a93528e)

![Screenshot 2023-08-03 012739](https://github.com/AnshulMaurya21/Automatic-Speech-Recognition-by-CTC/assets/87333511/c48a2e7e-7faf-4d42-97c4-4bf7dbae0acc)



