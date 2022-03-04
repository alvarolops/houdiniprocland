# Procedural Landscape Generator HDA
This Houdini Digital Asset bridges the gap between different types of generated content such as biome-based terrain, trees or road systems.

It can be imported into Unity projects that have Houdini Engine installed and a user interface with the different generation options of the asset will be shown.
The desired content is generated as game objects can then be freely used inside Unity. The modules that make up the asset are:
- Terrain
- Water
- Trees
- Details
- Rocks
- Paths

## How to install
In order to use this Houdini Digital Asset, one must install three separate elements: the Houdini Launcher, the Houdini Engine for Unity plugin and the asset itself.

Houdini can be installed for free through the launcher offered in its official website (https://www.sidefx.com/download/).

Once the Houdini Launcher is downloaded and installed, any Houdini components, including the recommended build of the Unity Engine Plugin, can be added to the computer.

Afterward, the Unity package that contains this plugin can be located with the name with the name “HoudiniEngineUnity.unitypackage” through the path “Program Files/Side Effects Software/Houdini Engine/” inside the drive where Houdini was installed.

To load the asset into a Unity project, with the Unity workspace open, one must navigate to the Assets tab and select “Custom Package…” inside the “Import Package” option.

Next, the aforementioned “HoudiniEngineUnity.unitypackage” file must be located in the computer’s file system and imported into the project in order to set up everything that the developed Houdini Digital Asset needs to operate.

Once the Houdini Engine plugin is added to the project, the .hda file can be placed anywhere inside the Project folder and then dragged to the current active scene to import it—this creates a game object which acts as the parent of the game objects produced by the generator and includes the special HEU_Houdini Asset Root component that represents the Houdini Engine interface with the constructed set of modifiable parameters.
## Images of a generated example landscape
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image1.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image2.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image3.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image4.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image5.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image6a.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image6b.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image6c.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image6d.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image7a.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image7b.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image8a.png?raw=true)
![alt text](https://github.com/alvarolops/houdiniprocland/blob/main/Example%20Landscape%20Images/image8b.png?raw=true)
