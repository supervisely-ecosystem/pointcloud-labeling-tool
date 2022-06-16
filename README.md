<div align="center" markdown>

# 3D LABELING TOOLBOX
## A complete solution for LiDAR annotation
Label comprehensive 3D scenes from LiDAR or RADAR sensors with additional photo and video context, AI object tracking and point cloud segmentation.


[Learn more ➡️](https://supervise.ly/labeling-toolbox/3d-lidar-sensor-fusion)

[![](https://img.shields.io/badge/supervisely-ecosystem-brightgreen)](https://ecosystem.supervise.ly/apps/supervisely-ecosystem/image-labeling-tool-v2)
[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack)
[![views](https://app.supervise.ly/public/api/v3/ecosystem.counters?repo=supervisely-ecosystem/image-labeling-tool-v2&counter=views&label=views)](https://supervise.ly)
[![runs](https://app.supervise.ly/public/api/v3/ecosystem.counters?repo=supervisely-ecosystem/image-labeling-tool-v2&counter=runs&label=runs&123)](https://supervise.ly)

<img src="https://user-images.githubusercontent.com/106374579/174057708-fc7f4673-808a-4ce0-a256-5fe8c0f8f304.jpeg"/>
</div>

<br/>
<br/>

<div align="center" markdown>

### DESIGNED FOR 3D
# Practical tools for point cloud labeling
Annotation of point cloud scenes is not an easy task. Inspired by professional software like Blender, Supervisely offers user-friendly instruments to work with thousands of points.

`Cubiods`  |  `Lasso` | `Landmarks` 
:---------------:|:-----------------:|:-----------------:
<img src="https://user-images.githubusercontent.com/106374579/174058527-db0d24d8-cea8-43fc-9fc8-8d5cc1e311bc.gif" width="auto" height="auto" width="500" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174058625-4c134e10-e389-454e-81fd-ecfbe81962f6.gif" width="auto" height="auto"/>|  <img src="https://user-images.githubusercontent.com/106374579/174058759-6ef728ec-b294-42dd-997f-4aa240cb03d1.gif" width="auto" height="auto"/>

</div>
<br/>
<br/>

<div align="center" markdown>

### POINT CLOUD NAVIGATION & ANNOTATION
# 3D Object detection and Classification

</div>

Visualization and, especially, labeling of spatial point clouds is not a simple task. Apart from plain and well-understood image labeling, to successfully complete annotation project in 3D space we need to solve three additional challenges and provide:

* User-friendly navigation in three dimensions.
* Handy tools for accurate object detection.
* Maximum information for correct classification.

<div align="center" markdown>

## Voyaging the three-dimensional space

Before you can identify and label an object of interest you need to see it clear from every angle. To let some sunlight into the scene, we have introduced widely known navigation from video games with WASD keyboard controls to move around point cloud and mouse to control the camera angle.

Along with additional viewports with top-side-front perspectives using orthographic projections, it gives accurate representation of what you are dealing with.

`WASD and mouse navigation`  |  `Top-Side-Front viewports` 
:---------------:|:-----------------:
<img src="https://user-images.githubusercontent.com/106374579/174060827-cf223d71-2d3f-4734-8f93-262712a67dc7.gif" width="500" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174061103-f03a4760-0f0b-4742-b8c3-838f6f76c6ac.gif" width="500" height="auto"/>

`1M+ points with GPU-acceleration and rendering options`  |  `Colormaps` 
:---------------:|:-----------------:
<img src="https://user-images.githubusercontent.com/106374579/174062155-41a1784a-2203-4a06-aeef-10e40e1b60af.gif" width="500" height="auto"/>  | <img src= "https://user-images.githubusercontent.com/106374579/174062420-f2ccdbc7-71c4-4e0b-8df0-9d2037cb1f9b.gif" />

## Ultra-precise cuboid labeling
One cannot put a 3D box sitting behind a 2D monitor screen — that’s why having multiple viewports for editing a 3D box in multiple projections is a key to accurate annotation.


`Accurate 3D box labeling in top-side-front projections`  |  `Roll, pitch and yaw heading angle` 
:---------------:|:-----------------:|
<img src="https://user-images.githubusercontent.com/106374579/174063252-df9fdda9-1121-47fd-aea7-eaaf79d6ca22.gif" width="500" height="auto" width="auto" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174063450-d666eb2c-4efb-44a9-88f6-38e16a519009.gif" width="auto" height="auto"/>

 `Auto frustum culling to highlight the actual object`  | 
 |:-----------------:|
 <img src="https://user-images.githubusercontent.com/106374579/174063823-35e8c8e9-0c66-48c2-998b-144df7b0cfc0.gif" width="500" height="auto"/>

 ## Sensor fusion with adding photo & video context
Provide more information for accurate labeling and identification with photo and video context. Supervisely automatically calculates correlation between 3D space and 2D context and projects your labeled objects on it, letting you achieve unprecedented quality of labeling.


`Object projection on cameras`  |  `Multiple camera views` 
:---------------:|:-----------------:|
<img src="https://user-images.githubusercontent.com/106374579/174065016-5a902570-28e6-41ab-9131-be20496b99ff.gif" width="500" height="auto" width="auto" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174065275-0c299938-bb0c-46af-a628-1c414bc99acf.jpeg" width="500" height="auto"/>

 `Move camera to the same position as you see on a photo`  | 
 |:-----------------:|
 <img src="https://user-images.githubusercontent.com/106374579/174065512-577e8143-d584-4646-80e2-78282bb8928a.gif" width="500" height="auto"/>
 </div>

<br/>
<br/>
<div align="center" markdown>

### MULTI-FRAME 3D POINT CLOUDS
# Putting time in perspective

In many tasks such as autonomous cars localization and mapping (SLAM) and lane detection you have to label not just a single point cloud, but a series of clouds, called episodes. Supervisely provides labeling toolbox specially designed for such a case.

## Point cloud episodes

Just like as specially designed [video labeling toolbox](https://supervise.ly/labeling-toolbox/videos) is remarkably more performant than annotation of separate frames in [image toolbox](https://supervise.ly/labeling-toolbox/images), specially designed 3D episodes toolbox is surpassingly more excellent in every aspect from playback speed to tracking performance.

 <img src="https://user-images.githubusercontent.com/106374579/174066950-f725db02-4925-43ab-bf6f-22054c5fc255.gif"/>

 ## Timeline panel is your multi-purpose navigation guide

It’s easy to get frustrated with hundreds of clouds and objects labeled.

Episode timeline panel provides overall structure, answers questions like what is already labeled and simplifies editing tag segments and tracked objects.

 <img src="https://user-images.githubusercontent.com/106374579/174067179-1dcd8996-8c25-454c-a2a0-86de85e5f36b.png"/>
 </div>

<br/>
<br/>
<div align="center" markdown>

### 3D OBJECT TRACKING
# Track moving objects in LiDAR
A common task is labeling of a moving object across multiple point clouds. Supervisely offers built-in AI tracking algorithms that automatically detects and tracks objects of various classes, as well as more classic linear interpolation and other methods of object tracking.

`Tracking algorithms`  |  `Annotation objects built with hundreds boxes` 
:---------------:|:-----------------:|
<img src="https://user-images.githubusercontent.com/106374579/174068069-317e6e7b-45e8-4a2d-a268-928e71bf3d26.gif" width="auto" height="auto" width="auto" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174068436-7e11f0e2-8ee2-4026-b76a-06d3592e6b72.gif" width="auto" height="auto"/>

`Merge multiple objects together`  |  `Split object by frames` 
:---------------:|:-----------------:|
<img src="https://user-images.githubusercontent.com/106374579/174068744-4640cc39-c4c7-466b-8f35-24cf3be82e62.gif" width="auto" height="auto" width="auto" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174069064-42eeff3c-80c4-492a-a7ca-9df132801d05.gif" width="auto" height="auto"/>

`Copy and paste objects between point clouds`  |  `Color highlighting of IDs` 
:---------------:|:-----------------:|
<img src="https://user-images.githubusercontent.com/106374579/174069290-835f02e7-5682-4bdd-b8ca-1bdd04cfb45d.gif" width="500" height="auto" width="auto" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174069511-bc680d10-a948-4047-9e12-9ae659756029.jpeg" width="500" height="auto"/>

</div>

<br/>
<br/>
<div align="center" markdown>

### 3D INSTANCE SEGMENTATION
# Precise point cloud segmentation
3D semantic segmentation of cloud points is quite challenging. But with the right tools Supervisely provides, classifying of even the most spatial point clouds becomes much easier.

<img src="https://user-images.githubusercontent.com/106374579/174070181-a1ad5989-d9f9-4f00-9579-ca3c4949ee70.gif"/>

</div>

<br/>
<br/>
<div align="center" markdown>

### 3D SEGMENT TAGGING
# Tagging of 3D point cloud segments
Attach additional information to annotation objects or just tag specific segments of 3D point cloud episode with semantic, such as “what’s going on here”.

<img src="https://user-images.githubusercontent.com/106374579/174070580-5fd71a9b-bbda-43bd-b570-f21c109bcf4c.gif"/>

</div>

<br/>
<br/>
<div align="center" markdown>

### FEATURES
# All the right tools for PROs
Object detection, classification and segmentation are not the only tasks solved with Supervisely — there is always more to it!
`Randomize object colors`  |  `Hotkeys` | `Restore mode` 
:---------------:|:-----------------:|:-----------------:
<img src="https://user-images.githubusercontent.com/106374579/174071353-7e53f53d-44e8-46e1-8198-3752960d7f35.gif" width="500" height="auto" width="500" height="auto"/>  |  <img src="https://user-images.githubusercontent.com/106374579/174071549-5235517d-76e3-4700-b85a-84ae1d6c0f63.jpeg" width="500" height="auto"/>|  <img src="https://user-images.githubusercontent.com/106374579/174071614-97224fbe-4ad1-414a-a622-d68fcf52f644.jpeg" width="500" height="auto"/>