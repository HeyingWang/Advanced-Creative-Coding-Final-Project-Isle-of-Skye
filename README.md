# Advanced-Creative-Coding-Final-Project-Isle-of-Skye
CCI-CC-S1-Final Project by Heying Wang

•	[Intro]
Isle of Skye uses mainly Shader technology to create a 3D scene with islands, trees, moving figures and floating objects.

•	]Technology used for implementation]
Sound: Oscillation, maxiClock, Loading Sample and other sound parts coding
Animation & Scene: Mainly in Shader
(1)	Use the shader to create the animation of the blocks
(2)	Use the shader to create the ocean foam and wave motion effects
(3)	Use the shader to create the Island scene (terrain Noise)

•	[Difficulties]
(1)	Create a sky box with the right amount of light
(2)	Let the BOX walk


•	[Design Process]
(3)	Why choose this scene?
    For a holiday trip to Isle of Skye,I want to create a magical world which one likes Isle of Skye through coding.
(4)	How to create this world?
    I have divided the construction of the scene into sections.
The first part is the sky. I revisited the construction of the sky box
 (https://reije081.home.xs4all.nl/skyboxes/)  . Based on online open resources, I tried different sky colors but the results were not as good as I would have liked.  I chose to tweak the color of one of the sunset skyboxes, I think its color is also more in keeping with the fantastical effect I was looking for.

The second part is the construction of the ocean, which is actually more of an adjustment to planeGeometry. To make waves, I used the calculateSurfaceVertexShader( ) to change the size and distance of the waves, and set the time of waves.

The third part is the construction of the island scene. Firstly, I referenced the tree resource and set its height, width and number. Secondly, by creating multiple Boxgeometry and the vertexParameters. These unified parameters unite to build the carton villain that can act around the trees. 
 
 
The fourth part is the construction of the floating objects. I initially wanted to create seagull-like water birds, but found the shapes too complex and not magical enough, so I came up with the idea of creating floats by simply randomising the squares in the same way as before.

As well as creating a visual landscape, I also added a song by RADWIMPS, and through the sound part of the coding I had learnt I added the silver of Harp and Guitar to create my own soundtrack.

So that's all the design part of it. I actually think coding itself is full of magic, you may not fully anticipate what you've made until you render it, and there are always wonderful rewards to be had, and maybe that's the fun part of it.

•	[Further improvement]
I would like to add something like seagulls and more complex walking stuff, such as the ones in the movie Soul.
 

    


Reference link:
https://www.redblobgames.com/maps/terrain-from-noise/
http://mathworld.wolfram.com/DiskPointPicking.html
https://reije081.home.xs4all.nl/skyboxes/


Related link:
•	MIMIC
https://mimicproject.com/code/cc0058a3-55a5-3811-edb1-02e41167238b
•	Video
https://youtu.be/enT4uknxP4E
•	Github
https://github.com/HeyingWang/Advanced-Creative-Coding-Final-Project-Isle-of-Skye
•	Blog
https://hey-ing-wang.com/2021/01/11/texture/


•	[Other introductions]
Project Decription file is in this zip.
Sound sources：
（1）	Mimic by me: https://mimicproject.com/code/cee6fb07-ab2a-fa39-0afd-8a584d9f81ad
（2）	BGM: RADWIMPS - 你的名字。（Tropical House Vocal Mix）（HimSherlock remix）by HimSherlock
PS：Wait 1-2 seconds for the file to load before the sound and graphics are perfect




