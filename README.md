# bpcore-project-template

A project template for games using https://github.com/evanbowman/BPCore-Engine.

Add your code in main.lua. Add graphics by editing the tilesheets in the tiles/, sprites/, and overlay/ directories.

I've sized each tilesheet and spritesheet to the maximum size supported by the engine. You can of course use multiple different images, and swap them as needed with the `txtr()` function. Add any new images to the manifest.lua file.

The build script treats RGB(0xff, 0, 0xff) as a transparent color, so the image files contain a pinkish hue. You may use up to 15 other colors per image file.

To build your project, simply run build.lua in the top level directory. The only dependency is an installation of lua 5.3.
