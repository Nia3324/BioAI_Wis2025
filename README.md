## The Limits of Attention-Based Adaptation

This project works on replicating and testing the STAR algorithm on Whisper-tiny in 4 different accents of the Common Voice Dataset. 
It is divided in 5 notebooks.

- DataExtraction: Using the full CommonsVoice Dataset, we extract a segment of data of each desired access.
- DatasetCreation: Generates the dataset for Zero-shot,Real-Labels and Pseudo-Labels training and testing.
- Whisper: Trains and tests the Zero-shot,Real-Labels and Pseudo-Labels. 
- STAR: Main file where we generate the STAR dataset, train and test the STAR adapted model.
- Plots: Here we plot the results to obtain self-attention matrices, confusion and attention and variances.

For this project the following packages are required:

- torch==2.5.1+cu121
- torchaudio==2.5.1+cu121
- numpy==2.0.2
- transformers==4.57.3
- tqdm==4.67.1
- jiwer==4.0.0
- openai-whisper

