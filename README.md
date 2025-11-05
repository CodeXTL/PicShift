# PicShift
## Overview
Welcome to the overview of the project (currently) known as PixShift. Inspired by the DIY Image Sensor and Digital Camera by Sean Hodgins (source), the goal of this project is to create a portable camera with a 64-pixel camera sensor that is mounted on a mechanically shifted stage so that images at a higher resolution can be obtained. The camera sensor will be created from scratch by laying out an 8 by 8 grid of light sensors (or phototransistors) on a custom PCB. Since an 8 pixels by 8 pixels image is not very interesting, we will mount the camera sensor PCB on a motorized mechanical XY stage so that we may shift the small senser over a wider area to capture multiple samples in order to stitch them into a higher resolution image. The stitching of samples will be done through software on a STM32F411RET6 microcontroller, residing on the NUCLEO-F411RE development board. The resulting image data will be saved onto a microSD card through a breakout board. For focusing the light onto the sensible region, we plan on using an existing convex lense (perhaps a magnifying lens or some kind of camera lens) 

## Objectives
-	Design and create a working PCB for an array of 8 by 8 light sensors
-	Design and create a mechanical XY stage in a small form factor.
-	Design and create a body to house all components so that the final project is portable.

## Expectation
The expectation for the project is quite simple. The final product should be able to take an image at the click of a button, store that image onto a microSD card, and when we open the image on a computer, it should resemble the scene. If it can do all that, that is an ‘A’. And the measure of even greater success would just be how much more we can make the image resemble the scene; the clear, the better. 

## Mid-Project Review Goal
By the time of the mid-project review, I aim to have the following deliverables:
-	A working camera sensor PCB
-	A prototype for the motorized XY stage

## Cost
Work-in Progress

## Resources
-	Instructables: DIY Image Sensor and Digital Camera
  -	Github: LINK
-	YouTube: Microscope Automated XY Stage: 3D Printing test
  - They salvaged a CD-ROM drive and made a highly precise XY stage for microscope slides
  - The motor from the CD-ROM drive is apparently called a sled motor, which seems like a stepper motor attached to a very long screw (might look for alternatives if it becomes hard to acquire an old CD drive)
-	st.com: User Manual for NUCLEO-F411RE
-	DigiKey: ALS-PT19-315C/L177/TR8
-	LCSC: EVERLIGHT ALS-PT19-315C/L177/TR8
