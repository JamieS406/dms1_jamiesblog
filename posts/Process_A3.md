---
title: Process shots Assignment 3 (Week 9)
published_at: 2024-05-18
snippet: Assignment 3 progress
disable_html_sanitization: true
---
# **Assignment 3 Progress**
**Refinements**
![skybox](/process_a3/pa3_skybox.png)
*Skybox testing*
- After discussion with my classmates, there was a suggestion to try a sunrise scene as my skybox. I made several attempts at this, including adjusting the dimensions of the original image to make the skyline sit at a nicer level and smooth out the image seam where the image wraps back around itself. 
- After several attempts I decided to use a model as it looked better than the image (of which the quality is greatly reduced when so extensively expanded), and it also had a very beautiful lighting setting that I could play around with.

![sprite](/process_a3/pa3_sprite.png)
*Making the barriers invisible*
- I took quite a few attempts to make my barriers invisible. First, I tried doing so in the same way I made translucent water. However, the edges of this "transparent" material could still be seen, resembling glass. 
- I eventually discovered a material function of the "sprite" material called "mask" which made the material truly invisible.

![vista](/process_a3/pa3_vista.png)
*Framing the vista*
- The final vista scene after coming out of the portal had to be framed well. 
- My criteria for the final scene was: It had to be expansive, include the sun in the frame, have the branches of the cloud tree visible and the other cloud trees growing and thriving together visible in the distance. I actually rotated the tree, moved and reangled the clouds as well as rotated the whole skybox multiple times before I got the final framing that I wanted.
- I even positioned the ambient music of this final state towards the sunrise, so that the players are prompted to look in that direction.

**Classmate Feedback + Improvements**
In class, we play-tested each others' game environment, and I had the privilege of getting several of my classmates to go through mine. They were excellent help... especially when they endeavoured to find as many loophooles in my environment as possible (and fully exploit what it afforded them) 😂. 

![Breaktree](/process_a3/pa3_breaktree.png)
*The Climbing Tree loophole*
- The first bug discovered was that my invisible barrier did not close off all possible routes to fall off the suspended platform on the tree. Combined with the barrier also not being very tall, my players were able to jump off the tree, climb branches, and free-fall off the face of the earth, much to their delight. I promptly fixed that, so no more tree-climbing for them (sorry Milo and Mataso you were great).

![Breakpot](/process_a3/pa3_breakpot.png)
*The wall loophole*
- As I had changed the first-person controller to be a model that can climb and jump, it appeared my players climbed the walls and found a single wall section that I had not put a mesh collider on. Therefore they managed to find a way out of the pot fixture and onto the terrain, which was definitely not supposed to happen. Quickly got that fixed.

![feedback](/process_a3/pa3_feedback.png)
*Other Feedback*
- I got some other specific feedback I requested on sound and clarity of prompts. It appeared the maze section was a little too quiet for my players, and it was not sufficiently obvious to my players that they were meant to step onto the portal in the middle of the room to enter the final state.

![soundmaze](/process_a3/pa3_soundmaze.png)
*Sound tweaks*
- I added more sound points in strategic corners of the maze so that the ambient music will be more comprehensive.

![ptwinkle](/process_a3/pa3_ptwinkle.png)
*Portal being more obvious*
- I took inspiration from my classmate Matilda's beautiful firefly feature in her game build, and realised I could put sparkles together with the "twinkling" sound effect I had existingly over the portal to make it more obvious one is meant to stand over the area. 

**Final Reflections**
- Wow.. what a ride this was. When I began this 3D design section I had absolutely no experience with Unity, never heard of prefabs or skyboxes or gameobjects before, and felt both intimidated and nervous about my capacity to finish this assignment on time. Learning 3D software from scratch, AND code? Goodness, This might really be the end for me. 
- It has been exciting, fufilling and very fun discovering all the different things I can do in the 3D environment. I got to learn so many things together with my classmates, finding joy in their progress and being pleasantly surprised with my own. I surpassed my own expectations of my capabilities as well, somehow finishing the assignment well within the time frame given.
- Definitely there were a lot of troubleshooting moments, backtracking and searching up and stressing about bugs, but it does feel like it was all worth it in the end. I have a lot more confidence in trying out more 3D software and I'm excited to see where this takes me in future!

# **Attribution List**

**Model Attributions**

Unity Asset Store
DryTrees
Digital Antichrist
Standard Unity Asset Store EULA - Extension Asset
https://assetstore.unity.com/packages/3d/vegetation/trees/dry-trees-86967

Sketchfab
“Head in the Clouds”
Duznot
CC Distribution
https://sketchfab.com/3d-models/head-in-the-clouds-7b338c7fecbd4acc99fa9a77e7c7a932

Unity Asset Store
Breakable Jars, Vases, Pots
Pixeled Bun
Standard Unity Asset Store EULA - Extension Asset
https://assetstore.unity.com/packages/3d/props/furniture/breakable-jars-vases-pots-280906

Unity Asset Store
“Sunrise – Sunset – Night – HDRIs – 4k”
HDRI Haven
Standard Unity Asset Store EULA - Extension Asset
https://assetstore.unity.com/packages/2d/textures-materials/sunrise-sunset-night-hdris-4k-178134

Unity Asset Store
“25+ Free Realistic Textures – Nature, City, Home, Construction & More”
Game Buffs
Standard Unity Asset Store EULA - Extension Asset
https://assetstore.unity.com/packages/2d/textures-materials/25-free-realistic-textures-nature-city-home-construction-more-240323

Unity Asset Store
“Modular First Person Controller”
JeCase
Standard Unity Asset Store EULA - Extension Asset
https://assetstore.unity.com/packages/3d/characters/modular-first-person-controller-189884

**Sound and Music Attributions**

Storyblocks
“Deepness”
Efliz
No Attribution Required
https://www.storyblocks.com/audio/stock/deepness-348029658.html

https://assetstore.unity.com/packages/2d/textures-materials/25-free-realistic-textures-nature-city-home-construction-more-240323

Valentine’s Day Night
The Turquoise Moon
Storyblocks
No Attribution Required
https://www.storyblocks.com/audio/stock/valentines-day-night-s2eldn4qpkhpp9gh3.html

Storyblocks
“Magic Chimes on Wind”
- 
https://www.storyblocks.com/audio/stock/magic-chimes-on-wind-bxqvbe3hivsk0wxrtvi.html
