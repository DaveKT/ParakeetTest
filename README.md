# Parakeet Transcribe Test

This repository contains a Jupyter notebook for evaluating the accuracy and performance of an implementation of the Parakeet models for Apple Silicon using MLX engine ([Parakeet MLX](https://github.com/senstella/parakeet-mlx)). The test compares transcriptions of multiple audio inputs and helps explore the model's behavior on different types of speech.

## Notebook Overview

**Notebook**: `ParakeetTranscribeTest.ipynb`

The notebook performs the following:

- Loads and plays audio files.
- Runs transcription using the Parakeet model.
- Outputs the transcribed text.
- Compares transcription accuracy across different audio samples.
- Includes sample transcription outputs stored in `audio_file_output.txt` and `audio_file2_output.txt`.

## Audio Transcription Samples

The repository includes transcriptions from two example audio files:

| File                   | Summary                                                                 |
|------------------------|-------------------------------------------------------------------------|
| `audio_file_output.txt` | Experimental or unintelligible content, showcasing model limitations.   |
| `audio_file2_output.txt` | Clear reading of the U.S. Constitution preamble, showing accurate transcription. |