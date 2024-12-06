# GreasePencil Keyframes -Legacy
Timeline and Keyframe utilities for Grease Pencil animators living in the past.
- ***Tested on Blender 3.6.16***
- Besides compatibility, the only other difference between this and the 4+ version is the Dope Sheet's +5 and +10 buttons are always set to '*Start at Playhead'*, so initially you should position the playhead where you want the keyframes added.

## Features
### N-panel
In the 3Dview's N-panel under the Grease Pencil tab, you'll find a panel called Grease Pencil Keyframes.
- **Keyframe Count**: add blank keyframes to the selected Grease Pencil layer
- **Spacing**: specify how far apart your keyframes will be spaced
- **Start from Playhead**: Position the playhead where you want your new blank keyframes to start from. Otherwise, blank keyframes will initially be added at frame 1, or appended to the end of the current sequence of keyframes.
- **Add Keyframes** button. Once you've entered the things, ***be sure to select the layer you want the keyframes added to***, then hit this button.

![image](https://github.com/user-attachments/assets/05bb86f7-760b-4721-8af3-bf6005f384d8)
 
### GP Timeline Toolbar
A couple of buttons and a timecode readout on the Dope Sheet's Grease Pencil toolbar:
- **+5**: this button adds 5 blanks on twos ***to the selected GP layer***, starting at the position of the Playhead.
- **+10**: this button adds 10 blanks on ones ***to the selected GP layer***, starting at the position of the Playhead.
- **Time**: timecode in seconds and frames

![image](https://github.com/user-attachments/assets/c4ec29ac-5feb-4daf-8a5f-5aac55397ff5)

# Installation
1. Click the big green **<>CODE** button above, and choose *Download ZIP*.
2. In Blender, go to *Edit > Preferences > Add-ons* tab
- Top-right > *Install..*
- Browse to where you saved the above `.zip`
- Click Install
- Don't forget to enable the add-on with the checkbox
![image](https://github.com/user-attachments/assets/a013c15b-4b0d-4044-84e0-84881e056b2a)
