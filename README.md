# chronusmetronome
Metronome for research with microrhythms and note onset. Developed by Alex Fraga.

Chronus - Microrhythm Metronome (MAX/MSP Patch)
This repository contains a customizable microrhythm metronome developed using MAX/MSP. The patch allows users to manipulate the timing of rhythmic onsets in real time, supporting practice, teaching, and research in expressive timing. It is helpful particularly in research on Brazilian music traditions like samba and choro.

This tool was developed as part of my doctoral dissertation:
Samba, Suingue, and Microrhythms: Note Onset as Expressivity in Pandeiro de Choro Performance.

Overview
The metronome features:

- 8 customizable onset slots, each adjustable between -50% and +50% delay.
- Preset loading and saving for microrhythm profiles.
- Pandeiro sound samples.
- Visual pannel that can help guiding listening.
- Pre-loaded onset proportions found in samba and pandeiro performances used in my research.

How to Use
1) Open the patch in MAX/MSP.
2) Switch to Presentation Mode.
3) In the top left corner, turn on: Metronome and Audio (both buttons should appear green)
4) Set the tempo: Type the desired BPM in the BPM box. Press TAB to confirm.
5) Set rhythmic configuration: for my research, I set # of notes to 4 and set Subdivision to 4 (remember to press TAB after each input)
This configuration will generate 4 onsets per beat, activating 4 sound samples on the rightmost panel.

Interface Breakdown
Reference Metronome (2nd panel from left to right)
This is an evenly spaced reference click. Helps compare “straight” rhythm against microrhythmic versions.

Preset Panel (3rd panel from left to right)
Load preset microrhythm profiles used in samba and choro or save your own proportions into the coll object for future use.

Main Delay Panel (Right)
Each onset includes:
- A dial for adjusting delay percentage (-50% to +50%)
- A float number box to manually enter the delay %
- A reset button (labeled 0) to return to zero delay
- A read-only box showing actual delay in ms (do not edit)
- The list of sound samples I sued throughout my research

Troubleshooting
If you’re not hearing audio:
Make sure both Audio and Metronome are ON (green).
Check Audio Settings in MAX.
Try resetting the BPM, and click on a saved proportion to reapply values.
Ensure volume is not muted on your device.

What's Included
microrhythm_metronome.maxpat: Main patch

sounds/: pandeiro samples

presets/: Proportions from dissertation research

LICENSE: Creative Commons BY-NC 4.0

README.md: This guide

License
This project is licensed under
Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).
You may share and adapt this work for non-commercial purposes, with proper attribution.

Citation
If you use this patch in your teaching or research, please cite:

Fraga, Alex. Samba, Suingue, and Microrhythms: Note Onset as Expressivity in Pandeiro de Choro Performance. Doctoral Dissertation. University of Toronto, 2025.
