# GD Explorer

GD Explorer is an asset explorer addon for Godot. It allows you to browse your asset library 
in a dedicated tab, prior to importing. 

Check out the showcase video here: https://www.youtube.com/watch?v=YOonjwOQJgg

# Image Explorer

The image explorer currently supports .png and .jpg, but all supported Godot types will be coming
soon. 

Controls include: Zoom in/out, filtering options, tiling, modulation, and background options.

# Model Preview

Model Preview currently supports .gltf, .glb, but all supported Godot types will be supported soon.

3D camera controls are still in progress, but currently you can change the background env, and switch camera to ortho.

# Audio Preview

Audio Preview currently supports .wav, .ogg, but all supported godot types will be supported soon.

Controls include: Pause, play, restart, paning, looping, and a spectrum analyzer (note: Requires adding the filter to the main bus)

# Text Preview

You can also technically preview text files (e.g., markdown, text, licenses)

# Font Preview

Font preview supports oft, ttf, among others. Will add proper editing soon, so you can write your own preview text.

# Material Preview

This one will be much tricker, because there is so many differnt material types and such. Probably no support for now.

# TODO

 - Fix log spam related to the SpectrumAnylyzer missing by default
 - Prevent all files from being expanded when clearing the search
 - Importing 3D model switches tabs
 - Add better 3D controls
 - Re add support for text files
 - Fix issue with icons dissapearing from dropdown
 - Fix texture filtering not working consistantly
 - Fix the filesystem from being cleared on godot close
 - Allow moving images


# Release Notes

## 0.0.3

 - Files with the same name no longer clash with each other 
 - Project root is now cached. Will add more settings later.
 - Add better icons for resource types
 - Check cache when starting up, to try and provide icons on load
 - Create cache folder and other important files on startup, if missing

## 0.0.2

 - Fixed issue where the 'gde.txt' dummy file was deleted rather than copied, preventing you from importing more than one asset.
 - Fixed log spam when input was processed before the main control node was available.
 - Added editor-friendly icons to the audio preview

## 0.0.1

 - The first testing release. Contained generally the feature set claimed above, but a bit buggy and badly organized.

 
