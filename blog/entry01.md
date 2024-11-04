# Entry 1
##### 11/4/2024

# Content
## Context

The tool I've decided to create my platformer game on is Godot. Godot is a game engine mainly used to develop 2D & 3D games, cross-platform projects, and more. I chose Godot after reviewing 2 other tools. Unity and Gdevelop. The other two tools, especially Unity. The reason I chose Godot over those two is because of how much more accessible Godot is. There seems to be a bigger community, newer community around Godot which seems to be the problem with Unity. Unity has been long established but because of this many resources are old and prone to being outdated.

## Setting Up and Tinkering
Setting up Godot was nothing special as I just had to download the engine off of their website and then create a folder for the game I will be running in order to save it. Getting started with Godot there are two sections, 2D and 3D in which this case I will be making a 2D platformer so I'll be focusing on the 2D aspect of Godot. To help me get started on Godot I simply browsed on Youtube on starter guides and I started with this [tutorial](https://www.youtube.com/watch?v=5V9f3MT86M8&t=393s) in particular. It goes over the basics of using 2D Godot to make platformers. Following the tutorial was a lot of implementing items and moving around settings. Some things in particular that I've learned is what nodes and children nodes are which you create and designate in order to create your proejct. There are also properties of a node which depends on whatever node your using. For example, the TileMap node like the name suggests creates a tile surrounding your canvas and by allocating your own assets you can add images to those tiles. Examples of properties within a node would be scale, rotation, material, texture, and more depending on the type of node it is. I tinkered around with these settings the most to see what each of these do. One of the more important settings for any asset or texture based node is the filter setting. When allocating pngs to your canvas or any image will have changed quality based on how much you scale it. In order to keep the same quality regardless of scale you would filter it to "Nearest" which keeps the original image while scaling it the way you want as well. Using all of this I so far have created nodes to make up a map, character, and hitboxes. The current part of my project is filling up the scene with a canvas and objects. The next step is to allocate code into these assets so action can be implemented such as moving a character and using the collision in order to collide with objects

## Skills
* I am following the tutorial in order to learn more about creating a platformer in Godot but I am also going outside of just following. I am tinkering by moving around settings on my own and trying things out. Doing this prevents me being locked to the tutorial only.
* It is important to take in information instead of "doing". I find this to be a very important aspect of learning as it is a difference between copying and understanding. I make sure to understand the concepts of nodes and such.

[Next](entry02.md)

[Home](../README.md)