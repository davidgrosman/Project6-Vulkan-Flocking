# University of Pennsylvania, CIS 565: GPU Programming and Architecture.
Project 6: Vulkan Flocking: compute and shading in one pipeline!
===============

## User resources
- **Name:** David Grosman.
- **Tested on:** Microsoft Windows 7 Professional, i7-5600U @ 2.6GHz, 256GB, GeForce 840M (Personal laptop).

### Demo Video/GIF

![](img/Preview.gif)
![](img/PreviewTwo.gif)

### Project Analysis

1. __***Why do you think Vulkan expects explicit descriptors for things like generating pipelines and commands? HINT: this may relate to something in the comments about some components using pre-allocated GPU memory.underline bold italics***__

2. __***Describe a situation besides flip-flop buffers in which you may need multiple descriptor sets to fit one descriptor layout.***__

3. __***What are some problems to keep in mind when using multiple Vulkan queues?***__
 * **Take into consideration that different queues may be backed by different hardware**
 * **Take into consideration that the same buffer may be used across multiple queues**
 * **What is one advantage of using compute commands that can share data with a rendering pipeline?**

### Blooper
![](img/Video.gif)

### Credits

* [Vulkan examples and demos](https://github.com/SaschaWillems/Vulkan) by [@SaschaWillems](https://github.com/SaschaWillems)
