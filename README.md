# TTT
Transition Table Tools

![Package logo](/icon.png)

## About
In this repo you will find abstractions that will help build transition tables for music pitch succession. These transition tables (TT) are helpful for algorithmic composition using quantum computers as demostrated by [BMA](https://github.com/iccmr-quantum/Miranda_Basak_Demos).

__TTcomp__: allows the composer to create TT by dialing in the exact weights to each transition.

__TTperf__: allows the performer to generate TT just by sending in raw MIDI data.

__TTnorm__: is used by both _TTcomp_ and _TTperf_ to make sure the TT values are normalized.

__BMA+TTperf__: is an example of using _TTperf_ with [BMA](https://github.com/iccmr-quantum/Miranda_Basak_Demos).

## Installation
Before starting, make sure you have [Max](http://cycling74.com) installed, as well as [The QAC toolkit](http://quantumland.art/qac) Max package.

Clone or [download](https://github.com/Quantumland-art/TTT/archive/refs/heads/main.zip) this repo and unzip it somewhere in the Max path (e.g. Documents/Max 8/Library).

## Feedback and Getting help
Make sure to learn about these tools by exploring the help patches and carefully reading the reference pages.
For bugs and other feedback, please open a [new issue](https://github.com/Quantumland-art/TTT/issues/new).

Also, please consider learning more about Max [here](https://cycling74.com/get-started), and [Intro to Quantum Computer Music](https://github.com/Quantumland-art/Intro-to-Quantum-Computer-Music) Tutorial, as well as explore the other projects in [QuTune's Github](https://github.com/iccmr-quantum).

## Acknowledgements
This repo was created by Omar Costa Hamido as part of the [QuTune Project](https://iccmr-quantum.github.io/).
