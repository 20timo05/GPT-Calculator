# Teaching simple Arithmetic to a small Transformer
The goal of the GPT is to learn simple arithmetic operations such as (+, -, *, /). The architecture is based on the famous Paper [Attention is All You Need](https://arxiv.org/pdf/1706.03762), but is a Character-based Language model and only includes the Decoder. In theory, the GPT should learn the underlying algorithms behind simple operations through self-attention, without being explicitly told how to do this.

# Purpose
This GPT is obviously not intended for any Real-World use, but it is a great learning Project to put everything I have learned about NLP from Andrej Karpathy's Video Lectures, specifically the [Neural Networks: Zero to Hero](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&si=A7wmUXohjjnHA6My) playlist and 3Blue1Brown's [Video on Self-Attention](https://youtu.be/eMlx5fFNoYc?si=xZJUevr2iAHhz_yM). This project specifically is the Swole Dog Project from Exercise 2) in [one of his lectures](https://youtu.be/kCc8FmEb1nY).

# Starter Code
The starter code is my own implementation of the Transformer Architecture similar to [this one](https://youtu.be/kCc8FmEb1nY). It is trained on a concatenation of all Harry Potter Books and therefore is only able to generate Harry Potter like Text (see: `./output/HarryPotterText.txt`) (although the text does not make sense).