iOS OpenGL boilerplate
===============

The minimal amount of code needed to draw a single triangle on iOS devices.

Background
========

When I was searching how to start making OpenGL games on iOS, I looked for examples, but couldn't find a good one — all of them went overboard with creating this, abstracting that. I didn't need to learn that, I know that already — just gimme the minimal amount of code to draw a triangle — I'll go from there on my own.

The Xcode project wizard spews about 10 files, which is way more than bare minimum, so I ended up making one — one `.m` file, one `.plist` file and one `.pbxproj` file.

To keep code brief, we use OpenGL ES 1.0 to omit shader setup, projection setup and pretty much any other setup that would be required in OpenGL ES 2.0. I assume you know how to handle 2.0, you will need to change to `kEAGLRenderingAPIOpenGLES2` in `viewDidLoad` function.

It's up to you to figure out how to add functionality you want, Xcode has a very good documentation set — *__read it__*.

Requires:

 * Xcode 5.0 to compile
 * iOS 7 to run

You're free to take it and use it however you like.