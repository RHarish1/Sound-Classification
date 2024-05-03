# UrbanSound8K
Urban Sound 8K Classification Using CNN

## Dataset and Its Structure

1. **Urban Sound Classification Dataset**: The Urban Sound Classification dataset is a popular dataset widely used in sound classification tasks. It can be accessed through the [official website](https://urbansounddataset.weebly.com/).

2. **Understanding Dataset Structure and Feature Extraction**:
   - Regardless of the dataset used, it's crucial to comprehend its structure and methods for extracting necessary features.
   
3. **Downloading UrbanSound8K Dataset**:
   - The UrbanSound8K dataset can be downloaded from [this link](https://goo.gl/8hY5ER). Upon downloading, it yields a compressed tar file of approximately 6GB in size.
   
4. **Dataset Contents**:
   - Upon extraction, the dataset comprises two main folders: 'audio' and 'metadata'.
   
5. **Audio Folder**:
   - The 'audio' folder contains 10 subfolders named fold1, fold2, and so forth, each containing around 800 audio files, each lasting 4 seconds.
   
6. **Metadata Folder**:
   - The 'metadata' folder contains a CSV file with various columns such as file_id, label, class_id corresponding to the label, salience, etc.
   
7. **Detailed Description**:
   - More detailed information about the dataset structure and its contents can be found [here](https://urbansounddataset.weebly.com/urbansound8k.html).

## Research Papers and Resources to Follow

1. [Meyda](https://github.com/meyda/meyda/wiki/audio-features)
2. [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis/wiki/3.-Feature-Extraction)
3. [Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a)
4. [Urban Sound Classification Part 1](https://towardsdatascience.com/urban-sound-classification-part-1-99137c6335f9)
5. [Audio & Voice Processing with Deep Learning](https://www.analyticsvidhya.com/blog/2017/08/audio-voice-processing-deep-learning/)

## Recommended Library

- **Librosa Library**: This library can be installed using the following commands:
   ```
   pip install librosa
   pip install ffmpeg-python
   ```
   Librosa facilitates reading audio files and converting them into amplitude values for each sample. For instance, a 4-second audio file with a sampling rate of 22050 Hz translates to an array of size 88200, with each element representing an amplitude sample.
