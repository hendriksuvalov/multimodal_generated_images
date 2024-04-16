# multimodal_generated_images
A test set composing of different generated images for multimodal segmentation
Authors: Joonas Ariva, Hendrik Šuvalov



- static  elements: [(type, x,y,size, noise_level)]
- abnormalities: [(type, x, y, size), ...]
- background details : [gaussian noise]


static elements: 
- heart --> use heart symbol, roughly constant coordinates, slightlhy varying size
- kidneys: 2xellipse
- chest frame


abnormalities: 
- star, can only be near or inside kidney
- triangle, can only be near heart
- circle, can be anywhere 
