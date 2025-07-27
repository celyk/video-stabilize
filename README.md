[WIP]
This is a project for stabilizing video using OpenCV. I'm motivated by my own videos recorded from 2017-present that are high quality, but shaky as I never owned a gimbal.

Digital video stabilization can be achieved for free in Davinci Resolve with the click of a button, but I find that it doesn't quite suite my needs. If I make it that far, I will consider creating a plugin for Davinci.

Requirements:
- Stabilization without cropping/zooming in
- Inpainting to fill the empty space

This is ideal for me, as my footage is only 1080p and I don't want to sacrifice any resolution. 

For implementation, I think I will use OpenCV. It has these functions built in the [Video Stabilization](https://docs.opencv.org/4.x/d5/d50/group__videostab.html) module.

I know that at this point there are AI models that can do this better, and upscale to 4k, but that can wait. I only want to make my videos watchable.
