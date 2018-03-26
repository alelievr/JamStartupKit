# JamStartupKit 2D
A Unity kit of assets and scripts for game jams

### Installation
Clone this repo using `git clone https://github.com/alelievr/2D-JamStartupKit` to get the submodules.

Then you can rename the project inside `Project Settings > Player Settings > Product name`

### Assets included
+ [Post processing stack V2](https://github.com/Unity-Technologies/PostProcessing)
+ [2D extras (for tilemap)](https://github.com/Unity-Technologies/2d-extras)
+ [DOTween](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676)
+ [Cinemachine](https://www.assetstore.unity3d.com/en/#!/content/79898)
+ [JamKit](https://github.com/alelievr/JamKit)

### Modified project settings
Chnages done accordingly to [the project setup best practices](https://blogs.unity3d.com/2017/08/10/spotlight-team-best-practices-project-setup/)

+ Fixed timestep to 0.01666
+ Maximum Allowed Timestep to 0.1
+ Gamma color space (for web target else use linear)
+ Graphics jobs false (causes lag spike on old GPUs)
+ GPU Skinning to true
+ Anti aliasing to disabled
+ VSync to disabled
+ Asset serialization to force text
