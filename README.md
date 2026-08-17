# MATLAB Speech Processing App

MATLAB application developed to record, isolate, store and reconstruct spoken words and conversations.

## Overview

This project was developed using MATLAB App Designer as part of a university engineering practical.

The application records continuous speech and uses signal processing to identify and isolate individual spoken words. The isolated words are stored as audio files and can later be selected and combined to create sentences and multi-speaker conversations.

## Key Features

- Audio recording and playback
- Automatic word isolation using amplitude thresholding
- Detection of pauses between spoken words
- Audio waveform visualisation
- Individual word storage as `.wav` files
- Support for multiple speakers
- Sentence reconstruction from stored words
- Multi-speaker conversation playback
- Error handling through the graphical user interface

## Signal Processing

Recorded audio is analysed using amplitude-based threshold detection to identify sections containing speech.

The application detects the start and end of spoken segments and combines segments separated by short pauses to prevent a single word from being incorrectly divided.

The implementation uses:

- **Sample rate:** 8 kHz
- **Bit depth:** 24-bit
- **Channels:** Mono
- **Amplitude threshold:** 0.004
- **Maximum segment gap:** 0.3 seconds

## Application

The graphical interface was created using MATLAB App Designer and provides separate functionality for:

- Recording speech
- Viewing recorded waveforms
- Isolating spoken words
- Selecting a speaker
- Playing stored words and sentences
- Building and playing conversations

## Technologies

`MATLAB` `App Designer` `Signal Processing` `Audio Processing` `GUI Development`

## Project Context

This project was completed as part of university Signal Theory coursework and demonstrates practical application of audio signal processing, MATLAB programming, file handling and graphical user interface development.

## Author

**Roedine van der Merwe**  
B.Eng Computer & Electronic Engineering
