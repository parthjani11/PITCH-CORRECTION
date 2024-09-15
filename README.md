# Overview
In digital signal processing (DSP), pitch correction involves analyzing the frequency content of a vocal recording and modifying the pitch to match a desired target. This process is widely used in music production to correct off-pitch notes without needing multiple retakes.

# Features:
- **Pitch Detection**: Detects the pitch of input vocal recordings  
- **Pitch Correction Algorithm**: Adjusts detected pitch towards the desired value using a correction factor.  
- **Blending**: Offers customizable strength of correction to allow for a natural-sounding result.  
- **Real-Time Processing**: Applies windowed processing to efficiently handle longer audio signals.

# How It Works:
- **Load Audio File**: The audio is loaded and divided into frames.  
- **Windowing & Overlap**: The input signal is processed frame by frame using a windowing technique with 50% overlap.  
- **Pitch Detection (Placeholder)**: Detects the pitch of each frame (currently using a placeholder).  
- **Pitch Correction**: Corrects the pitch by applying a calculated correction factor and blends it with the original signal based on correction strength.  
- **Output**: The corrected audio is normalized and saved as a new audio file.

# Applications:
- Vocal tuning for music production.  
- Enhancing live performances by adjusting off-pitch notes.  
- Creating natural and professional-sounding recordings.
