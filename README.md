# Awesome Computer Graphics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/lhns/awesome-computer-graphics/master/media/rtow.jpg" align="center" width="1000">](https://github.com/petershirley/raytracinginoneweekend)

The Awesome CG List! A collection of various resources to learn computer graphics, including books, tutorials, online courses, and more. Name a CG topic, chances are this list contains some stuff about it (if not, it will someday!).

**If you want to contribute, please read the [Contribution Guidelines](contributing.md)**


## Contents

* **[What is computer graphics?](#what-is-computer-graphics)**
* **[How to get started?](#how-to-get-started)**
* **[I want to learn more advanced stuff](#i-want-to-learn-more-advanced-stuff)**
* **[Books](#books)** 
* **[Tools](#tools)**
* **[Courses](#courses)**
* **[Sites](#sites)**

### What is computer graphics?
Computer graphics is a knowledge area about how to create images using computers, to put it simply. Generally this is done by processing data representing information what you want to draw, for example: objects, colors, light. Anything about visual and digital creations have used CG in some way: games, movies, etc.

### How to get started?
Before showing a lot of books, videos, and materials, first you need to know what is bare-minimum to begin with computer graphics. It boils down to two main topics: programming and math. About programming, learn the basics, it's recommended 
to learn C/C++ as they are used frequently in this area. Concerning math, learn linear algebra and geometry, there are books in this list focused on math fundamentals for CG, pick one and work on it.

### I want to learn more advanced stuff
Assuming you know programming and math, then you can get more practical. It's a good approach to get a project about a topic 
like global illumination, or GPU programming to deepen your knowledge on this area. Examples of projects are: path tracers, 
photon mapping, shader programming. Recommended projects are the PBRT, the ray tracer from the [Physically Based Rendering](http://www.pbr-book.org/3ed-2018/contents.html) book, and the ray tracer with photon mapping, from the [Realistic Image Synthesis Using Photon Mapping](https://www.amazon.com/Realistic-Synthesis-Mapping-Revised-Paperback/dp/B011DC2J3O/ref=sr_1_1?s=books&ie=UTF8&qid=1540518657&sr=1-1&keywords=photon+mapping). Also, watching tutorials for [Shader Toy](https://www.shadertoy.com/) and experimenting on it is a good idea. 


### Books
* [Real-Time Rendering](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003/ref=sr_1_1?s=books&ie=UTF8&qid=1540516813&sr=1-1&dpID=51iw1UWKNhL&preST=_SX218_BO1,204,203,200_QL40_&dpSrc=srch), by Tomas Akenine-Moller, one of the best on high performance graphical applications, very detailed explanations and contains many examples to illustrate its topics.

* [Ray Tracing in One Weekend](http://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf), by Peter Shirley, a free book to get you implementing a basic ray tracer in C++, the catch is: this one is very short (about 40 pages), you'll learn the minimum to create a ray tracer to generate amazing images in a very short amount of time!

* [Ray Tracing: The Next Week](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20The%20Next%20Week.pdf), by Peter Shirley, builds on top of the first books' project, adding more effects, like textures and motion blur.

* [Ray Tracing: The Rest of Your Life](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20the%20Rest%20of%20Your%20Life.pdf), by Peter Shirley, last book of the series, exposes more mathematical themes necessary to build more complex and complete renderers.


* [Physically Based Rendering: From Theory to Implementation](http://www.pbr-book.org/3ed-2018/contents.html), by Matt Pharr, teaches how to create a ray tracer to render realistic images. A thorough explanation of the technique, with as much code the theory behind it, and has a free online version!

* [3D Math Primer for Graphics and Game Development](https://www.amazon.com/Math-Primer-Graphics-Game-Development/dp/1568817231/ref=sr_1_1?s=books&ie=UTF8&qid=1540517337&sr=1-1&keywords=3d+math+prime), by Fletcher Dunn, this book gives more focus to the math necessary for game development.

* [Fundamentals of Computer Graphics](https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/1482229390/ref=sr_1_1?ie=UTF8&qid=1541094572&sr=8-1&keywords=fundamentals+of+computer+graphics), by Steve Marschner, introduces graphics concepts. 

* [Ray Tracing from the Ground Up](http://www.raytracegroundup.com/), by Kevin Suffern, guides you through the task of implement a ray tracer, starting with a bare-bones project, and every chapter introduces a new concept to add to the renderer.

* [Advanced Global Illumination](https://www.amazon.com/Advanced-Global-Illumination-Philip-Dutre/dp/1568813074/ref=sr_1_1?s=books&ie=UTF8&qid=1540517779&sr=1-1&keywords=advanced+global), by Philip Dutre, its focus are fundamentals to understand realistic image synthesis, such as light transport.

* [Realistic Image Synthesis Using Photon Mapping](https://www.amazon.com/Realistic-Synthesis-Mapping-Revised-Paperback/dp/B011DC2J3O/ref=sr_1_1?s=books&ie=UTF8&qid=1540518657&sr=1-1&keywords=photon+mapping), by Henrik Jensen, teaches math and algorithms to implement the photon mapping rendering process. It even has a complete C++ implementation of the technique!

[//]: # " * The Ray Tracer Challenge](http://raytracerchallenge.com/), by Jamis Buck"

[//]: # " * Computer Graphics: Principles and Practice, by James Foley."

[//]: # "* Foundations of 3D Computer Graphics, by Steven Gortler."

[//]: # "* Computer Graphics Through OpenGL: From Theory to Experiments, by Sumanta Guha."

[//]: # "* Interactive Computer Graphics: A Top-Down Approach with WebGL, by Edward Angel."

[//]: # "* OpenGL Programming Guide: The Official Guide to Learning OpenGL, by Dave Shreiner."


### Tools
* [OpenGL](https://www.opengl.org/), one of the most, if not the most popular graphics API.
* [Vulkan](https://www.khronos.org/vulkan/), created by the same guys from OpenGL with the intent to provide an API with better performance than its predecessor.
* [Bonzomatic](https://github.com/Gargaj/Bonzomatic), live-coding edtior for OpenGL pixel shaders, where the results appear on background as you edit the code.

### Courses
* [Computer Graphics - San Diego](https://www.edx.org/course/computer-graphics-uc-san-diegox-cse167x-3), by Ravi Ramamoorthi, this course focus on learning the necessary math to program a offline ray tracer.

* [SIGGRAPH University](https://www.youtube.com/playlist?list=PLUPhVMQuDB_aWSKj7L_-3Ot_nxBze_YMy), playlist with popular courses from the annual SIGGRAPH Conference.

* [Computer Graphics & Imaging - Berkeley](https://cs184.eecs.berkeley.edu/), by Ren Ng (Spring 2018.)


### Sites
* [ScratchAPixel](https://www.scratchapixel.com/index.php?#_=_), teaches image rendering from basic to advanced.
* [Learn OpenGL](https://learnopengl.com/), resource site, contains tutorials by topic, code examples and even has a pdf version of its contents.
* [OpenGL tutorial](http://www.opengl-tutorial.org/), tutorial for learning OpenGL 3.3 or higher.
* [Learn Vulkan](https://vulkan-tutorial.com/), teaches the modern API, created by the same team that created OpenGL.
* [Shader Toy](https://www.shadertoy.com/), site to create, visualize, and share GLSL shaders.
* [Real-Time Rendering recommended books](http://www.realtimerendering.com/books.html), list of recommended books on the Real-Time Rendering's site.
* [Jendrik Illner's blog](https://www.jendrikillner.com/tags/weekly/), Illner works for Ubisoft as a 3D programmer, every week he posts a summary of articles about 3D graphics, like shader tutorials, real-time rendering papers, etc.
* [Ray Tracey's blog](http://raytracey.blogspot.com/), Sam Lapere's blog, leads the scientific team at EPFL Blue Brain Project. Lots of post about real time rendering.
* [Inigo Quilez's site](http://www.iquilezles.org/index.html), articles and shader demos from the co-creator of [Shadertoy](https://www.shadertoy.com/).

## Projects/Repositories
* [PBRT](https://github.com/mmp/pbrt-v3), source code for pbrt, the renderer described in the third edition of "Physically Based Rendering: From Theory To Implementation".
* [tinyrenderer](https://github.com/ssloy/tinyrenderer), course of computer graphics teaching how Opengl and rendering works, teaching how to build a simpler version of OpenGL.
* [Ray Tracing in One Weekend repository](https://github.com/petershirley/raytracinginoneweekend), ray tracer code based on Ray Tracing in One Weekend's book.
* [Fragmentarium](http://syntopia.github.io/Fragmentarium/), program to edit and visualize GLSL shaders, mainly focused on fractals and generative systems
* [Business Card Ray Tracer](http://eastfarthing.com/blog/2016-01-12-card/), as the name suggests, it's a very small ray tracer, 35 lines (minified) and file size is 1377 bytes.
* [Small PT](http://www.kevinbeason.com/smallpt/), path tracer made in 99 lines in C++.
* [Marble Marcher](https://codeparade.itch.io/marblemarcher), a game where you get to move a marble through fractal stages as fast as possible to reach the goal. This game is entirely ray marched, giving it a lot of cool visual effects ray tracing is not able to generate. 
* [3D Game Shaders For Beginners](https://github.com/lettier/3d-game-shaders-for-beginners), A step-by-step guide on how to implement SSAO, depth of field, lighting, normal mapping, and more for your 3D game.

## Miscellaneous 
* [Hacker News thread on learning computer graphics](https://news.ycombinator.com/item?id=14652936): thread dicussing on how to learn computer graphics, if you have no time to read the entire thread, [read this comment](https://news.ycombinator.com/item?id=14653343).
* [Computer Color is Broken](https://www.youtube.com/watch?v=LKnqECcg6Gw): video about how color representation/compression in computers can distort the blur effect.
* [The Art of Code channel](https://www.youtube.com/channel/UCcAlTqd9zID6aNX3TzwxJXg): tutorials on shaders using ShaderToy, mostly videos on procedural generation.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Luís Santos](https://github.com/lhns) has waived all copyright and related or neighboring rights to this work.

