# Awesome Computer Graphics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="./media/stormtrooper.png" align="center" width="1000">](https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-ray-tracing)

The Awesome CG List! A collection of various resources to learn computer graphics, including books, tutorials, online courses, and more. Name a CG topic, chances are this list contains some stuff about it (if not, it will someday!).

**What is this "computer graphics" stuff?**
Computer Graphics is a sub-field of computer science, that studies how to create images through computers, like games, movies and image editing. 

**If you want to contribute, please read the [Contribution Guidelines](contributing.md)**


## Contents

* **[What is computer graphics?](#what-is-computer-graphics)**
* **[What do I need to know to get started?](#what-do-i-need-to-know-to-get-started)**
* **[What if I want to learn more advanced stuff?](#what-if-i-want-to-learn-more-advanced-stuff)**
* **[Very relevant materials](#very-relevant-materials)**
* **[Books](#books)** 
* **[Libraries](#libraries)**
* **[Courses](#courses)**
* **[Sites](#sites)**

### What is computer graphics?
Computer graphics is a knowledge area about how to create images using computers, to put it simply. Generally this is done by processing data representing information what you want to draw, for example: objects, colors, light. Anything about visual and digital creations have used CG in some way: games, movies, comics, you name it.

### What do I need to know to get started?
Before showing a lot of books, videos, and materials, first you need to know what is bare-minimum to begin with computer graphics. Being an area about using computers, learning programming is essential. One approach is to learn programming
is doing a little project, to get used to programming logic. Besides coding, math is obviously necessary, since you will be
using it to manipulate data to create your results. Vectors, matrices, geometry, all of these are important.  
  
So, programming and math. If you have never studied them before, it can be overwhelming at first. To begin programming, take
a coding course, or tutorial to learn the basics. It is highly recommended to learn C/C++, as they are one of the most relevant 
languages in high-performance computer graphics. About math, you need to learn concepts from linear algebra, and to understand 
well geometry as a whole. A useful resource to begin is [this tutorial](https://www.scratchapixel.com/lessons/mathematics-physics-for-computer-graphics/geometry) from ScratchAPixel, where you can find very good explanations on this topic. 


### What if I want to learn more advanced stuff?
Assuming all of the above is old stuff to you, let's get more detailed. To master computer graphics it's necessary 
a very good knowledge of math: linear algebra, calculus, and geometry. Physics is important too, since CG can be (and is 
a lot of times) about simulating realistic phenomenon: refraction, caustics, radiance, indirect illumination. Programming is 
no different in its level of demand of expertise: good graphics programmers know about code and hardware optimizations, since 
they will probably create code to run in a GPU, that is used by an operanting system, so they need to fully understand what 
are their resources to run programs in a efficient way.    
There's no way around it to get more in-depth: learn linear algebra and calculus. Physics you can learn here and there, if you have to. One way to practice coding, is getting a project like creating a path tracer in C++, or another global illumination 
rendering process, like photon mapping.

### Very relevant materials
Regardless of your level of proficiency, this sections show excellent resources that are worth noting first, be it because 
their completness, relevance in the field, or any other quality. 


### Books
* [Real-Time Rendering](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003/ref=sr_1_1?s=books&ie=UTF8&qid=1540516813&sr=1-1&dpID=51iw1UWKNhL&preST=_SX218_BO1,204,203,200_QL40_&dpSrc=srch), by Tomas Akenine-Moller, one of the best on high performance graphical applications, very detailed explanations and contains many examples to illustrate its topics.

* [Physically Based Rendering](https://www.amazon.com/Physically-Based-Rendering-Theory-Implementation/dp/0128006455/ref=sr_1_1?s=books&ie=UTF8&qid=1540517251&sr=1-1&keywords=physically+based+rendering), by Matt Pharr, very code-focused book, goes back and forth between theory and its C++ implementations.

* [3D Math Primer for Graphics and Game Development](https://www.amazon.com/Math-Primer-Graphics-Game-Development/dp/1568817231/ref=sr_1_1?s=books&ie=UTF8&qid=1540517337&sr=1-1&keywords=3d+math+prime), by Fletcher Dunn, this book gives more focus to the math necessary for game development, this book does not cover topics like global illumination.

* [Ray Tracing from the Ground Up](http://www.raytracegroundup.com/), by Kevin Suffern, guides you through the task of implement a ray tracer, starting with a bare-bones project, and every chapter introduces a new conpect to add to the renderer.

* [Advanced Global Illumination](https://www.amazon.com/Advanced-Global-Illumination-Philip-Dutre/dp/1568813074/ref=sr_1_1?s=books&ie=UTF8&qid=1540517779&sr=1-1&keywords=advanced+global), by Philip Dutre, its focus are fundamentals to understand realistic image synthesis, such as light transport.

* [Realistic Image Synthesis Using Photon Mapping](https://www.amazon.com/Realistic-Synthesis-Mapping-Revised-Paperback/dp/B011DC2J3O/ref=sr_1_1?s=books&ie=UTF8&qid=1540518657&sr=1-1&keywords=photon+mapping), by Henrik Jensen, teaches math and algorithms to implement the photon mapping rendering process. It even has a complete C++ inplementation of the technique!

[//]: # ( * Computer Graphics: Principles and Practice, by James Foley.)

[//]: # (* Foundations of 3D Computer Graphics, by Steven Gortler.)

[//]: # (* Computer Graphics Through OpenGL: From Theory to Experiments, by Sumanta Guha.)

[//]: # (* Interactive Computer Graphics: A Top-Down Approach with WebGL, by Edward Angel.)

[//]: # (* OpenGL Programming Guide: The Official Guide to Learning OpenGL, by Dave Shreiner.)


### Libraries
* [OpenGL](https://www.opengl.org/), one of the most, if not the most popular graphics API.

### Courses
* [Computer Graphics - San Diego](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x-3), by Ravi Ramamoorthi, this course focus on learning the necessary math to program a offline ray tracer.

* [SIGGRAPH University](https://www.youtube.com/playlist?list=PLUPhVMQuDB_aWSKj7L_-3Ot_nxBze_YMy), playlist with popular courses from the annual SIGGRAPH Conference.

[//]: # (* [Computer Graphics & Imaging - Berkeley](https://cs184.eecs.berkeley.edu/, by Ren Ng (Spring 2018.)


### Sites
* [ScratchAPixel](https://www.scratchapixel.com/index.php?#_=_), teaches image redering from basic to advanced.
* [Learn OpenGL](https://learnopengl.com/), resource site, contains tutorials by topic, code examples and even has a pdf version of its contents.
* [OpenGL tutorial](http://www.opengl-tutorial.org/), tutorial for learning OpenGL 3.3 or higher.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luís Santos](https://github.com/lhns) has waived all copyright and related or neighboring rights to this work.

