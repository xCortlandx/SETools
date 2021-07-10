A .SE format import / export plugin for Maya (2022+)

.SE formats are open-sourced formats optimized for next-generation modeling and animation. They are free to be used in any project, game, software, etc with the hopes that people will adapt the standard unlike other formats available.

Animation format documentation: Specification
Model format documentation: Coming soon
Installation:
Download the latest seanim.py, semodel.py and SEToolsPlugin.py from the repo and save them in the following directory depending on your OS and Maya version:

C:\Users\dev\Documents\maya\2022\plug-ins\
Next, you must open the plugin manager using Window->Settings/Preferences->Plugin Manager once there find SEToolsPlugin.py and check off the following:

Loaded (Loads the plugin)
Auto load (Loads the plugin every launch)
Updating:
Replace the files in the correct directory from the installation section with the new ones AND delete all of the .pyc files. Go to "SE Tools->Reload" Plugin to finish. If an error occurs, you must simply reload Maya.

Usage:
Animations:

To import an anim use "SE Tools -> Import SEAnim File" or drag and drop a file, this will import an anim onto an already binded scene.
To export, either select the bones to use (or select none for all), set the end scene time to the animation end time, then use "SE Tools -> Export SEAnim File" this will export the animation to a .seanim file.
To place a notetrack use "SE Tools -> Edit Notetracks" this will open a menu for editing notetracks and removing them.
Models:

To import a model use "SE Tools -> Import SEModel File" or drag and drop a file, this will import a binded model with it's materials.
To export, either select the bones / meshes to use (or select none for all), then use "SE Tools -> Export SEModel File" this will export the model to a .semodel file.

This is based on version v4.0.0. Changes made from the source repo will also be updated here.