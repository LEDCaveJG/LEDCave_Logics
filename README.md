# LEDCave Plugin

The LEDCave Logics is an Unreal Engine Plugin, which contains the nDisplay Configs of the LED Cave Studios.
The Meshes in the Configs showing the LED Wall Setups in their actual size, so it can be used as a preview to get an idea about the dimensions of the Studio compare to the environment. As a placeholder, it is also useful for the production.

## How to use the Plugin

![SelectLogicSpawner](https://user-images.githubusercontent.com/117661104/225952057-872508f4-773a-4b76-9627-4a4419a732fa.PNG "All/Engine/Plugins/LEDCave_Logics Content/Spawn_Logic")

When the Plugin is installed, the nDisplay Spawner can be found
in the Content Browser under All -> Engine -> Plugins -> LEDCave_Logics Content -> Spawn_Logic. 
   When it is dragged in the scene, the nDisplay Configs can be spawned with it.
   
![SelectStudio](https://user-images.githubusercontent.com/117661104/225952461-abd24177-3d38-483d-8bd7-dd9a85716dbe.PNG "Selecting the studio and spawning the nDisplay Config")

With the "LC_Logic_Spawner" selected in the Outliner, the studio can be selected at the "LEDCave Logic Auswahl" and spawned by clicking the "Spawn LC Logic" Button.

![spawned](https://user-images.githubusercontent.com/117661104/225953055-9beb6c59-27b6-43f1-a9cc-1f4eb3247274.PNG "Spawned nDisplay Config")


### How to place the nDisplay Configs manually

![nDisplayConfig_Berlin](https://user-images.githubusercontent.com/117661104/225953390-69043ac7-faa5-478c-ae1b-1ed8e153fde6.PNG "Directory of the nDisplay Configs")

The nDisplay Config can be placed manually by dragging them directly from the Content Browser into the scene. The Configs are in the LEDCave_Logics Content folder  under LEDCaves -> LEDCave_+(selected Studio) -> NDISPLAY.

## How to activate the Plugin 

![CopyPluginsFolder](https://user-images.githubusercontent.com/117661104/225953739-8305fcae-8ba8-4600-a195-5a5a010447a8.PNG ".../UE_5.1/Engine/Plugins")

The Plugin Folder has to be copied into the Plugin folder of Unreal Engine. (.../UE_5.1/Engine/Plugins)

![Enable_Plugin](https://user-images.githubusercontent.com/117661104/225953956-22f0844e-7364-4ad0-8a65-51b037e2fc1c.PNG "Searching for LEDCave_Logics Plugin")
When the Project is opened, the Plugin can be searched and enabled in the Plugin window (Edit -> Plugins).

![RestartAfterEnableling](https://user-images.githubusercontent.com/117661104/225954160-233fa274-29fc-406d-9344-a4758320163b.PNG "restarting after enabling the Plugin")
After enabling the Plugin, the Project has to be restarted.

![ContentBrowserSettings](https://user-images.githubusercontent.com/117661104/225955315-10be7b4b-4777-4a48-b5e5-7bb018b5ec76.PNG "Content Browser Settings")
In order for the LEDCave_Logics Content folder to be found in the Content Browser, there has to be "Show Engine Content" and "Show Plugin Content" enabled in the Content Browser Settings (the Settings are in the upper right corner of the Content Browser window).


#TODOs

Git Authentifizierung mit Auto Account nicht automatisch
Git Install auskommentiert
Doku über Ordnerfreigabe (Sharing, Full Permission Everyone)

