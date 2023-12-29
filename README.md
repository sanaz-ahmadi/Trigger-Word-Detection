<ul>
  <li>Constructed a speech dataset and implemented an algorithm for trigger word detection.</li>
  <li>Synthesized and processed audio recordings to create training and development datasets.</li>
  <li>Built a network that ingests a spectrogram and outputs a signal when it detects the trigger word. Used 1-D convolutional layers, GRU layers, and dense layers.</li>
  <li>Utilized the trained model to make predictions and detect the trigger word ("activate") in audio clips.</li>
</ul>

### steps followed by code:
1. Data synthesis: Creating a Speech Dataset
   - Listening to the Data
   - From Audio Recordings to Spectrograms
   - Generating a Single Training Example
        - is_overlapping
        - insert_audio_clip
        - insert_ones
        - create_training_example
   - Full Training Set
   - Development Set
2. The Model:
   - Build the Model --> modelf
   - Fit the Model
   - Test the Model
3. Making Predictions --> Testing on Dev Examples
