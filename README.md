# Melodia: Algorithmic Music Composition in Python

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Melodia is a Python-based tool for generating musical compositions using algorithmic techniques. It uses machine learning and deep learning techniques to create unique and creative musical pieces. Explore the creative possibilities of code and music!

## CURRENTLY WORKING ON:

- Multi-track generation and multi hand piano support
- Better training data

## Features

- Generate unique musical compositions using your own MIDI files.
- Uses LSTM (Long Short-Term Memory) networks, a type of recurrent neural network, to learn musical patterns and generate new ones.
- Save and load trained models for later use.
- Export generated compositions as MIDI files.

## Installation

1. Clone this repository: `git clone https://github.com/TheKC33/melodia.git`
2. Navigate to the cloned repository: `cd melodia`
3. Install dependencies: `pip install -r requirements.txt`

## Usage

1. Prepare your example MIDI files and place them in the `examples` directory.
2. Run the training script: `python train.py`
3. After training, go into the play.py and change the model name to the model you just trained.
4. Run the play script to generate a new composition: `python play.py`
5. The generated composition will be saved as a MIDI file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.