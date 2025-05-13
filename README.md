For Maya v20+
Requires timeSliderBookmark.mll plugin

Maya Python script that allows to not only create bookmarks from animation sequences but also set keyframes at the start and end of each animation. 
This version provides more control and automation for animators working with TPL data.
If objects are selected, the script automatically sets keyframes at the start and end of the animation range for each object.
Each bookmark is assigned a random color for easy identification.
Automatically creates an animation layer for keyframes without interfering with existing layers.


1. If objects are selected:

Creates a new animation layer.

Sets keyframes at the start and end of each animation sequence for the selected objects.

2. If no objects are selected:

Only bookmarks are created.

Usage: 
Select the objects you want to keyframe before running the script.
If no objects are selected, only bookmarks will be created.
