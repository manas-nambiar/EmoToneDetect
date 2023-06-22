# EmoToneDetect
I've created this program to use the RAVDESS dataset to train a model and predict the emotion which is present in an audio recording. This is a foundational model which still requires constant change and I plan on implementing new and more accurate models and building off of those models. The scope of this project is to achieve a model that is ~93%< accurate and apply this model to real live recordings which can be provided in real-time or through the upload of a recording.

Used the RAVDESS dataset to create a program which uses various techniques to guess the emotion based on the features present in the audio.

The following description is directly from https://zenodo.org/record/1188976:

About Dataset Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) Song audio-only files (16bit, 48kHz .wav) from the RAVDESS. Full dataset of speech and song, audio and video (24.8 GB) available from Zenodo. Construction and perceptual validation of the RAVDESS is described in our Open Access paper in PLoS ONE.

Check out our Kaggle Speech emotion dataset.

Files

This portion of the RAVDESS contains 1012 files: 44 trials per actor x 23 actors = 1012. The RAVDESS contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Song emotions includes calm, happy, sad, angry, and fearful expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.

File naming convention

Each of the 1012 files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 03-02-06-01-02-01-12.wav). These identifiers define the stimulus characteristics:

Filename identifiers

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).

Vocal channel (01 = speech, 02 = song).

Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).

Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.

Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").

Repetition (01 = 1st repetition, 02 = 2nd repetition).

Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

Filename example: 03-02-06-01-02-01-12.wav

Audio-only (03) Song (02) Fearful (06) Normal intensity (01) Statement "dogs" (02) 1st Repetition (01) 12th Actor (12) Female, as the actor ID number is even.
