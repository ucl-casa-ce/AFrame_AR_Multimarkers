# AFrame_AR_Multimarkers
WebAR Multi-markers using AFrame and AR.js.

A simple multimarker example using AFrame (0.9.2) and AR.js (2.0.8). 
Live example here: https://ucl-casa-ce.github.io/AFrame_AR_Multimarkers/ (markers images are in the MarkerPng folder).
The browser will ask (the first time) to access the camera feed, if available. On iOS check if Camera & Microphone Access is On under Settings -> Safari -> Privacy & Security section.

How it works?
The index.html call the multiMarkersName.js script that create the <a-marker> tags using the PATT files in the resource folder. Each marker displays a text with its ID. Any other media can be added to the marker.
  
  ---------
  AFrame https://aframe.io/ https://github.com/aframevr/aframe/ <br/>
  AR.js https://github.com/jeromeetienne/AR.js
 
