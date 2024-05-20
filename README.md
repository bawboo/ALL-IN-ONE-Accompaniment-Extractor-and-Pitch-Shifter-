# Accompaniment-Extractor-and-Pitch-Shifter
用Facebook開發的Demucs model和Librosa等Python packages寫的簡單線上伴奏分離及移調程式(在Colab上運行)

內含中文說明，日後會上傳英文版本的使用說明．

A simple online accompaniment extraction and transposition tool developed using Facebook's Demucs model and Librosa, running on Colab.　　　　

[Accompaniment extraction and transposition tool (Chinese Version)](https://colab.research.google.com/drive/1MHk0PrDqzQPvazmfEav2l30bEPGcjF17?hl=zh-tw#scrollTo=WCwMs05xjh80)

The tutorial in this colab is written in Chinese. An English version will be added in the future.
Feel free to use it even if you don't the tutorial, all you need to do is:
1. Upload your audio( can be .wav, .mp3, .mp4, please use a filename without space or wierd characters)
2. Choose the transposition
3. Change the output_file_path variable to your uploaded filename.
4. Run all cells.
5. Download the output.wav(or .mp3)
If you upload a long audio or .wav or .mp4 file, it may take a long time to upload. Please check the audio file is uploaded before your run the final cell.


## Overview
This project is a simple online transposition tool developed using Facebook's Demucs(HTDemucs) model and Librosa, running on Colab. It allows users to separate accompaniment and transpose music tracks easily.

## Features
- Separate vocals and accompaniment from music tracks using Demucs.
- Transpose music tracks to different keys using Librosa.
- Easy to use with a Colab notebook interface.

## How to Use
1. Open the [Colab notebook](https://colab.research.google.com/drive/1MHk0PrDqzQPvazmfEav2l30bEPGcjF17?hl=zh-tw#scrollTo=WCwMs05xjh80).
2. Follow the instructions in the notebook to upload your music file.
3. Run the cells to separate the accompaniment and transpose the track.

## Credits
This project utilizes the following tools and libraries:
- [Demucs](https://github.com/facebookresearch/demucs): A state-of-the-art music source separation model developed by Facebook AI Research.
- [Librosa](https://librosa.org/): A python package for music and audio analysis.
- [Colab](https://colab.research.google.com/): A free Jupyter notebook environment provided by Google.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
Special thanks to the developers of Demucs for their incredible work in music source separation.



