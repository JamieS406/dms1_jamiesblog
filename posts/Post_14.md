---
title: Post 14 Week 9 Session 1
published_at: 2024-05-16
snippet: Exporting Game exercise + Assignment 3 progress
disable_html_sanitization: true
---
# **Exporting Game exercises**
![exportinggame](/w09s1/w09s1_exportgame.png)
*Exporting Configurations*
- Exporting my game out into web-ready play for others to explore was more complex than I had previously imagined. Unfortunately for me, it appeared that my game was too big to be web-playable 🥲. So I had to do a workaround by exporting it out as an application and zipped it so that it could be smaller. It's still over 300MB though... good grief...

# **Assignment 3 Progress**
![potmaterial](/w09s1/w9s1_materialno.png)
![potmaterial](/w09s1/w9s1_materialpot.png)
*Material Manipulation*
- The texture I imported for the pot, a brownish concrete, was too matte to look realistic when I first applied it to the maze model. I played around with the "smoothness" and "metallic" settings in the material options until I was able to get this slightly glazed, textured tile. I really like the effect it gives, it's a lot more visually interesting and realistic!

![transparent](/w09s1/w9s1_transparent.png)
*Cloud material testing*
- I wanted my clouds to look translucent and "light", so I played around with the material settings a little. I found the "sprite" material option and discovered also that reducing the colour opacity with this material type makes it even more translucent. I continued with this until I acheived my desired effect, seen here.

![terrainbonzai](/w09s1/w9s1_terrainbonzai.png)
*Terrain and light*
- For the inside of the maze, I wanted to create a more creepy, slightly cold environment. The first room is the "bonzai", the representation of stunted creative growth. I decided to give the bonzai pedestal an eerie, bluish spotlight which helped bring focus to the bonzai centrepiece in the middle of the room, and give the area a nice blue tint.

![reflection](/w09s1/w9s1_reflection.png)
*Skybox and Lighting*
- The environmental lighting kept affecting the inner walls of the maze, making the walls a warm sunset yellow. It completely ruined the claustrophobic ambience I was trying to create. After some quick research online, there were suggestions to 1. change the exposure of the skybox or 2. add a reflection probe to the indoor elements. I took quite a while manipulating the skybox features first but realised it ended up affecting the look of all the elements in the entire scene. Afterwards, I tried the 2nd method. This created a lovely shadow on the whole area! I applied the reflection probe to 2 strategic parts of the maze, and I think it's a good balance of visibility for the player and darkness for the environment design.

![parent](/w09s1/w9s1_parent.png)
![grasslead](/w09s1/w9s1_grasslead.png)
*Parenting + wayfinding methods*
- I wanted to create grass on the transitional level, to show the middling ground between the "outside open fields" and the "inner pot" state. I decided to create the grass from scratch as the models online looked too complex. Finding out about the parenting tool here was very useful: it's essentially a grouping function, and allowed me to create and duplicate a lot of grass patches.
- I tried to lead the player to the "portal" to go to the final state through several methods. First I made the grass patches trail towards the portal, which also had the greatest density of grass. Next, I made the portal have a glow, and added both a twinkle sound and the ambient sound of the final state onto the portal when the player approaches it. Finally, I made the "roots" of the plant move in the direction of the portal.

![gcollider](/w09s1/w9s1_gcollider.png)
*Collider removal*
- When adding the grass into my transitional layer's floor, I realised I couldn't walk over the shapes as they had colliders on. I decided it would make more sense game-play wise to remove the colliders for smooth walk-through.

![ceilingconfig](/w09s1/w9s1_ceilingconfig.png)
*Ceiling design*
- I wanted the transitional stage's ceiling to evoke a somewhat aspirational feeling. I previously wanted to try creating a ceiling with holes in the shape of constellations, a shadow of what the night sky might be like. However after some trial and error that didn't seem so feasible in the method I was using, so instead I made a ceiling of translucent roots interlacing with one another. I wanted it to mimic looking past tree branches into the tentative sky, or to the stars above.

![playerrigid1](/w09s1/w9s1_playerrigid1.png)
![playerrigid2](/w09s1/w9s1_playerrigid2.png)
![playerrigid3](/w09s1/w9s1_playerrigid3.png)
*Teleport character problems*
- In order to make my character teleport properly I had to make it a "rigid body". However to my shock and horror, it started spinning wildly the moment I hit "play" (first image). 
- I first tried to just apply "rigid body" to the capsule object within the controller, but that just made it fall in front of the camera and roll around in front of the screen, which looked really strange.
- After looking for troubleshooting options, it looked like I had to "freeze rotation" on the X, Y and Z axises of the player so that the player will not try to rotate with every collision with another object (ie. the floor, the walls, etc.)

![teleport2](/w09s1/w9s1_teleport2.png)
![teleport1](/w09s1/w9s1_teleport1.png)
![teleportno](/w09s1/w9s1_teleportno.png)
![teleportcollider](/w09s1/w9s1_teleportcollider.png)
*Teleport pad problems*
- After looking up the teleport tutorial, the code I entered into the script took quite a while to register into the unity system, but it worked! I was very happy considering I don't have the best luck with code.
- As you can tell, teleporting had to go through several rounds of troubleshooting. I really could not get collider to register my player and I could not figure out why. After some help from my classmate Milo, we figured out the the collider on the teleporter had to be elevated, and specifically a box collider. After some fiddling with the controls we finally got it to work!


Will keep working on the Assignment!!
