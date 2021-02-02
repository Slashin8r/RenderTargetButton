# RenderTargetButton

This blueprint turns a Render Target into a Clickable and Hoverable button. The Render Target can use a Scene Capture 2D camera for dynamic image updates or it can use a static texture such as a PNG. The background of the texture must be transparent. This asset is a single blueprint that is easy to use, just follow the steps below:



1) Duplicate BP_RenderTargetButton and rename it as you see fit (I will call it BP_RTButton01).

2) Add BP_RTButton01 to your menu (you will find it in the User Created category).

3) Set its Render Target and Render Material defaults.

4) Open BP_RTButton01 and go to the Event Graph to complete the Click, Hover and UnHover events.



Video Demo: https://youtu.be/dcUg0xfPFfY

Features:

 Custom Buttons created by Render Targets
 
 Custom Click Hit Testing
 
 Custom Hover and UnHover Hit Testing
 
Important Notes: Very large Render Targets will impact the performance of your game. A 2560x2560 Render Target reduced framerate by up to 25%.
