# Scripts for Maya

These scripts were originally written for Maya 2012 in python.

*   CameraMovementScale: Change the rotation, pan and zoom speed of the maya viewport camera. Helpful when zoomed into tight areas of large models.
*   Maya2UnityExporter: Exports the current scene as an .fbx, with textures, to a Unity assets directory with the same naming convention as the current Maya Scene. Can freeze (non-deformer) transforms, deletes history, centers pivots, etc, and version up the current Maya Scene on export. Features a one-click export, which will export the current scene to a unity assets folder depending on the scene name. Can separate production assets and development assets (may require an exposed GUI option). Texture files will be exported with the Maya Scene object. Dialog settings are saved in an xml file.

![Screenshot](/CameraMovementScale/screenshot.png?raw=true "CameraMovementScale")
![Screenshot](/Maya2UnityExporter/screenshot.png?raw=true "Maya2UnityExporter")