# OpenGL projects

[Projects reference](https://github.com/users/srele96/projects/2)

## Project list

- 3D Model Viewer
- Terrain Generator
- 3D Game
- Ray Tracing
- Audio Visualizer
- Particle System

## Trade offs

I was thinking whether I should use OpenGL wrapper library but one Reddit comment from a guy who claims he has been working with GL for 20 years says that GL is global state machine and it doesn't play well with object oriented programming. That made sense since I've read that OpenGL is a state machine.

[Reddit reference](https://www.reddit.com/r/opengl/comments/8wos9k/opengl_wrapper_library/)

I decided to listen to the advice and use OpenGL as is with it's C api. One thing I could do is wrap ugly c strings and void pointers in functions or put it all inside a namespace to hide those... I will try.

