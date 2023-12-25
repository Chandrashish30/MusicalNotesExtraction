# Audio Signal Processing Project

This MATLAB script analyzes and recreates musical notes from an audio file. The example uses Beethoven's "Für Elise" (slow version), but the script is adaptable for other songs.

## Getting Started

1. **Prerequisites:**
   - MATLAB installed.
   - MP3 audio file in the same directory as the script (e.g., "FurElise_Slow.mp3").

2. **Initial Setup:**
   - Open MATLAB and navigate to the script directory.

3. **Run the Script:**
   - Execute the script step by step or all at once.
   - Plots and audio playbacks are included.

## Script Overview

1. **Loading and Preprocessing:**
   - Load audio, speed it up, and plot the waveform.
   - Analyze a specific window of the song.

2. **Downsampling:**
   - Reduce computational load by downsampling.
   - Plot the original and downsampled signals.

3. **Thresholding for Note Detection:**
   - Apply a moving threshold to identify notes.
   - Plot the original and detected notes.

4. **Frequency Analysis:**
   - Perform FFT on detected notes to find fundamental frequencies.
   - Plot frequency spectra for each note.

5. **Note Playback:**
   - Recreate the song using sine waves for each detected note.
   - Play back the recreated song and display musical notes.

6. **Additional Function:**
   - `FreqToNote` converts frequencies to musical notes.

## Customization

- **Input Audio:**
  - Replace "FurElise_Slow.mp3" with your audio file.
  - Adjust `t1` and `t2` for a specific song portion.

- **Downsampling and Thresholding:**
  - Modify downsampling factor (`m`) for optimization.
  - Adjust thresholding parameters for better note detection.

## Notes

- **Audio Output:**
  - Audio playback is muted by default. Set `mute` to `false` for audio.

- **Results:**
  - May vary depending on input audio quality.

- **Visualization:**
  - Plots visualize original signal, downsampled signal, detected notes, and frequency spectra.


Feel free to reach out for questions or improvements!
