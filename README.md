# Mini-map Demo RGDC 2017
## By Ben Hoffman
Mini map tutorial in Unity using render textures

Unity version 2017.1.1f1


# Steps to Follow
1. Open the "MiniMapDemo_StartScene" scene in the Scenes folder
2. Create a new camera, place it at your player's position. Name the camera something like "Minimap Camera"
3. Set the Y value to something around 10 - 15, and the X rotation to 90.
4. Set the camera projection to an Orthographic camera.
5. You can remove the GUI Layer, Flare Layer, and Audio listener components from the camera, because we don't need them.
6. Create a "RawImage" UI object by right clicking in the Hierarchy, selecting UI > Raw Image.
7.  Right click in the Project window, and create a Render texture.
  Right click > Create > Render Texture
8. Name this something like "MinimapTexture"
9. Drag this render texture on the "Target Texture" property of the minimap camera.
10. In the Raw Image that we created, set the "Texture" property to the render texture as well.  
11. You now have a minimap that works, but it does not follow your player. To do this, we will create a simple follow script for the minimap camera.
12. Tada! Yay minimap! You can add in some UI masks if you feel like it in order to make it look better, or possibly put some image effects on the minimap camera in order to change how that looks.
