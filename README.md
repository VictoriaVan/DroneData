# DroneData

Images for "quadcopter" and "syma drone" were scrapped from Google images.  

To avoid possible duplicates of quadcopters & syma drone, I flipped the images for syma drone vertically.  



# Annotating Fun

I'm using LabelImg.  
https://github.com/tzutalin/labelImg

Follow installation instructions. I'm using Python 3 + Qt5, but idk if it matters.
For labelImg > data > predefinedclasses.txt, you can get rid of the cat, dog, etc. and just put "drone" since we're only having 1 class.

There's like probably 1175 images. 


Run LabelImg, and make it "Open Dir" images_quadcopter or images_syma_drone and just draw nice boxes around the drones.  MAKE SURE YOU SAVE.  (It'll yell at you, so you probably won't forget.)

It's easy to set the output directory to annotations_quadcopter or annotations_syma_drone (whichever one you're labeling).  They're all going to be combined later.  

Thanks a bunches :) 


