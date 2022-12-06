<div align="center" markdown>
<img src=""/>  

# Annotation Tools

<p align="center">
  <a href="#Overview">Overview</a> •
  <a href="#How-To-Run">How To Run</a> •
  <a href="#Acknowledge">Acknowledgement</a> 
</p>

[![](https://img.shields.io/badge/supervisely-ecosystem-brightgreen)](https://ecosystem.supervise.ly/apps/supervisely-ecosystem/import-youtube-videos)
[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/import-youtube-videos)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/import-youtube-videos.png)](https://supervise.ly)
[![runs](https://app.supervise.ly/img/badges/runs/supervisely-ecosystem/import-youtube-videos.png)](https://supervise.ly)

</div>

# Overview

## Bounding Box (BBox) as an annotation tool
#### The BBox is used to quickly and easily determine the location of objects in an image.
1. On the left toolbar, select the **rectangle tool** or press **6** on the keyboard.
2. Assign a class to the selected tool. To do this, enter a title and select a color.
<img src="https://user-images.githubusercontent.com/119248312/205755949-c7582012-960b-4a4a-81f7-fb504b8d95d7.gif">

3. Limit the object, by placing two points that are opposite each other at different corners of an object. If necessary, correct the position of the points, by holding and dragging them.
4. To complete the editing and create a new rectangle, press the check mark in the top left corner or **SPACE** on the keyboard.

<img src="https://user-images.githubusercontent.com/119248312/205759156-9b35a41c-ab92-4db2-891e-aa1e1dec171c.gif">


## Polygon annotation tool
#### The Polygon tool is used to more accurately determine the shape and position of the object in the image.
1. On the left toolbar, select the **polygon tool** or press **8** on the keyboard.
2. Assign a class to the selected tool. To do this, enter a title and select a color.
<img src="https://user-images.githubusercontent.com/119248312/205759281-afa0b2e3-739d-449e-9146-62802bc40539.gif">

3. To select an object, place points consecutively **(SHIFT+1)** along its outline.
<img src="https://user-images.githubusercontent.com/119248312/205759319-125e9f4b-29cf-4ebd-a50b-83488bf2e65d.gif">

4. You can correct the location of the points, by holding and dragging them, as well as add more points **(SHIFT+Click)** or remove unnecessary ones **(SHIFT+2)**.
<img src="https://user-images.githubusercontent.com/119248312/205759463-74aa2a39-655d-43c5-9f23-27666b50cbb6.gif">
<img src="https://user-images.githubusercontent.com/119248312/205759517-a03b07d3-8716-40b0-94b7-ac093ec1bbf2.gif">

5. To complete the editing and create a new polygon, press the check mark in the top left corner or **SPACE** on the keyboard.
6. To create a hole inside a polygon, place points along the perimeter of the part to be cut.
<img src="https://user-images.githubusercontent.com/119248312/205759551-ec792d8c-55ef-479d-93cd-e567d6c88aaa.gif">



# How to Run

0. Create *.txt* file with a list of YouTube links to videos that you would like to download, just like in the example shown below:

```md
https://www.youtube.com/watch?v=nuYLz1CjRf0
https://www.youtube.com/watch?v=psGDf2VrvK8
https://www.youtube.com/watch?v=M69gZrLm9oc
```

1. Go to Team Files
<img src="https://user-images.githubusercontent.com/115161827/202218609-485003e6-e295-4d3b-9bd5-fa302e43eea2.png" >

2. Upload *.txt* file that contains YouTube urls
<img src="https://user-images.githubusercontent.com/115161827/203781775-acde06c1-4035-4d74-a9b8-0386c0850f8c.gif">

3. Right click to file and run the app from the context menu
  <img src="https://user-images.githubusercontent.com/115161827/203782776-dc90fb85-05d8-4cc0-a761-6c18db4b4f16.gif">


## Result

As a result of running this app, project with all of your uploaded videos will appear in your workspace.

<img src="https://user-images.githubusercontent.com/115161827/203787133-aaea00c0-7246-40b9-9023-f4131e753e26.gif"  style='padding-top: 10px'>


# Acknowledgement
This app is based on the great work `youtube-dl` ([github](https://github.com/ytdl-org/youtube-dl)). ![GitHub Org's stars](https://img.shields.io/github/stars/ytdl-org/youtube-dl?style=social)
