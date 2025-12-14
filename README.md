# Scaling-Law-Musical-MIDI-Data--ML-Project
This is machine learning optional project for understanding the scaling laws on MIDI data
This code repository contains 4 jupyter notebook which has been divided into parts.

The first notebook is part1 Data Collection and cleaning.ipynb which contains the data collection from the MIDICaps files and converting it to ABC format. Then we converted it to get the tokens using midi2acaps. Finally we are creating the vocabulary using the tokens and then finally we create the train.bin, test.bin, val.bin files using this.

The second notebook Part 2a - Tiny model training using nanoGPT.ipynb contains the training code for nanoGPT. This I trained on 29 Million parameters and was a fast training to understand the pattern of data optimization.

The third part Part 2 3 4a - Transformer LSTM training.ipynb contains code for transformer, LSTM based training and then selecting the best working transformer that we would use to generate music.

The fourth part Part4-GeneratingMusic.ipynb contains the music generation, post processing and music which can be played directly using the inline player.
<img width="969" height="852" alt="image" src="https://github.com/user-attachments/assets/c08a0a56-c07c-45c5-b78f-fc4f58531ac3" />

<img width="1474" height="606" alt="image" src="https://github.com/user-attachments/assets/98f8438e-7ce0-46b9-bd03-117a77071099" />
