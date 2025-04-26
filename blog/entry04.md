
# Entry 4 
##### 03/17/25

### Content:

This whole week, I've focused on animating my character for the Godot game that I made with backgrounds that I can design and I managed to get my characters moving left to right with different movement in between that are called "animations" and here are some snap shots of the animations for my characters: <br>

![godot Left animation character picture](PicRight.png) <br>

The picture above is supposed to be for the character  moving to the left and how his movements are supposed to change when the direction changes.

Take a look at the picture below:
![godot Right animation character picture](PicRight.png)<br>


This picture above is how the character moves when the player wants to move right. 

Since I had already finished working on creating sprites and making them run, I managed to get animations to kick in as they move from left to right!
I used `AnimatedSprite2D` and created animations for walking up, down, left, and right. (You basically draw or create the sprites each movement as you move left from the start, and they loop it to play it as an animation). 

Firstly, the animations didn't even work because I when I tried to run the animation, I completely forgot about calling the `.play("animation_name")` code and then later my animation was playing way too fast so I decide to play around with framing orders and adjust the speed of the sprites to make it seem more natural instead of going super duper fast when it's not needed. I also had to make sure the animation looped correctly instead of skipping each frame.

After the production of my animation, I hope to create animations that allow my character/sprite to have a standing animation where they bounce up and down instead of standing still when they have no movements at all, with checking for collisions.

### Sources:

Some of the sources that I used, of course, include YouTube videos.
Here are some YouTube videos that I skimmed to see how to create characters and animation
- [Gdquest](https://www.youtube.com/watch?v=5V9f3MT86M8)
- [Godot Engine For Animation](https://docs.godotengine.org/en/stable/classes/class_animatedsprite2d.html) 

These are the two main resources that I used to help create my animation figure. I recommend watching YouTube videos that have other people teaching you how to make action games with Godot because it taught me how to create my own sprite, how to use it, what it's used for, and essentially be useful in my project.

### Engineering Design Process:  
The current EDP step that I'm on is number 6, which is  **Test and evaluate the prototype** – I tested the sprite animations in-game and noticed they weren’t behaving how I thought it was supposed to. Therefore, I decided to test all my outcomes and see what would happen if I changed the frames and speed of the player's animation.
### Skills:
There are a lot of skills that I used, but the main skill that I learned is 
- Using Godot’s animation tools (`AnimatedSprite2D`)  
- Identified and fixed issues in animation playback  
- Practiced debugging and visual polish in game design  

In my next entry, I hope to see myself create animations of sprites having a bouncing up and down effect.

[Next](entry05.md)  
[Home](../README.md)
