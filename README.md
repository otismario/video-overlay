This is a guide on how to create a web page that has a video playing in the background and has another content displayed above it.

A few take away on how to understand this clearly, you will need to do he following.
* Have a video already saved in an acceptable format
* Create your basic html boiler plate, basic css knowledge to add beauty to your page and if you wish, add         
  some javascript as i did.

******  CSS EXPLANATIONS  *******

******  Video Section  *******  
In the class fullscreen-video, setting the position to absolute, top and left to zero (0), width and height to 100vh and 100vw respectively will cause the video to cover the entire screen and the overflow set to hidden will hide the scroll bar that may appear. 

******  Overlay Section  *******  
As seen in the class header-overlay, it takes the same properties as the class of fullscreen-video, except for the background, opacity and z-index properties. 
The opacity can be set to the users choice and the z-index will send the overlay in front, making it to lie above the video.

******  Content to be displayed above the video  *******  
Using the class header-content, set the z-index to a higher number if you want it to lie above the video and the header-overlay, in this case i set it to 2 and margin to auto. 


Thanks for visiting and reading through.
