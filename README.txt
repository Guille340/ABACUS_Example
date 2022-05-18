EXAMPLE
========

This is an example of audio and navigation data processing with ABACUS.

The folder contains the following:

- "block" folder: it includes the inputs and outputs from the software.

   # "acousticdb" folder: Acoustic Database folder with three consecutive
      Acoustic Database Files.
   # "audiodb: folder: Audio Database folder with three consecutive Audio
      Database files.
   # "configdb" folder: Configuration Database folder containing a set
      of populated configuration files and tables to be read on a single 
      processing block. The "Other" folder a few addional examples of 
      audioDetectConfig files for different detection settings (Moving 
      Average detector, and Neyman-Pearson detector with estimator-correlator 
      algorithms).
   # "detectiondb": Detection Database folder containing the PerformanceData
      file generated for the NP energy detector ('ed') and the associated ROC 
      curves.
   # "navigationdb" folder: contains the Navigation Database file.

- "sample_data" file: contains the audio and position data.
   # "Data_Audio" folder: audio data of the audio files to be processed, in 
      WAV and RAW formats.
   # "Data_Position" folder: PAMGuard depth and AIS/GPS tables (*.csv), and 
      SeicheSSV GPS/P190 position files (*.gpstext, *.p190).

- "root.json" file: contains the absolute paths for the audio data, position
   data, and processing block. Copy this file within ABACUS root directory,
   where the runAbacus.m function is found. Replace <PARENT_DIRECTORY> with
   the parent directory where ABACUS is saved. The paths must point at the
   location of the "Data_Audio", "Data_Position", and "block" folders mentioned
   above.

[Guillermo Jiménez-Arranz, 11 May 2022]