# Tool Learning Log

## Tool: **Godot**

## Project: **JJK PLATFORMER**

---

### 10/20/2024:
* I will be using the 2d element of godot
* Your scene is the thing that contains all the elements you add
* Throughout the 2d canvas, the blue box represents your game window
* I downloaded a pack full of assets such as backgrounds. Based on the tutorial I'm following I added a background png from the texture pack into the file. Using this I created a new node, TextureRect and dragged the png into it to create our background.
* Creating a new node child node, TileMap allows me to give it a terrain based on the texture pack and access terrain material from that texture pack. With it I can add tiles and create a map.
* ![alt text](image1.png)

### 11/4/2024:
* Added tiles outside of the map eliminating the chance of my character falling out boundaries
* Added CharacterBody2D Node
* This Node takes in two children nodes, sprite for the image it will be defined with, and collider with collision and hitbox purposes
* Subsequently added Sprite2D node and CollisionShape2D node as children of CharacterBody2D. We give the Sprite2D node a image, used for the sprite, then the collison node gives us a boxed collision box that we can size on our own
* There are different shapes and sizes you can change the collider into
* There is an issue with this though, when moving the sprite and its hitbox they are separate. We need to create a subscene for those two to be one object
* We create a scene in the Character node which basically saves all contents of the subfiles such as sprite and collision as one object. In order to edit them we can simply open up this scene where we will see the two folders separate again.
* Note (In order to save an edited scene simply press CTRL + S)
* 

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
