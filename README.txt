# ol_glsl - a collection of PUREDATA patches that use glsl shaders 
==================================================================

this is a collection of patches i made for my own personal purposes,
after having searched the web for glsl shader scripts that can be used
with Gem/Puredata.

These patches need the Puredata libraries "Gem" and "zexy".

All help patches should work out of the box (apart from the
image and movie files that must be loaded seperately.
and should give a detailed description how those abstractions can be
used in a Gem scenario.

The patches were tested and working with PD 0.49 under windows 7 and macos.

I adapted some of the the original glsl scripts so they would fit the Gem/PD
conventions and can be loaded with the corresponding glsl objects. The
sources of the original glsl scripts are:

https://github.com/Blackhart/GLSL-Shaders/tree/master/glsl
http://001.vade.info/?cat=6
https://github.com/b01xy

many thanks go to IOhannes Zmoelnig and Cyrille Henry for their
help in putting this together

# INFO

every shader is located in a seperate folder, consisting of:

[shadername].vert
[shadername].frag
[shadername].pd (this will be the GUI)
[shadername].txt (containing param + defaults, presets and probably other infos)

all .vert and .frag files must have unix line ending ! (LF)


====================================================================


original files were downloaded from:

https://github.com/b01xy/glsl

chromakey, lumakey, gaussianblur, edgeDetection:
https://github.com/Blackhart/GLSL-Shaders/tree/master/glsl

v001, blackandwhite:
http://001.vade.info/?page_id=20

fractal, twirl, deforme_texture:
https://github.com/thomasfredericks/Tvestroy

also nice:

https://www.youtube.com/watch?v=9_9XZoerIuU

maybe in the future but is GLSL ES:

https://www.shadertoy.com/


# LICENSE/COPYING

- Copyright (c) IOhannes m zmoelnig
- Copyright (c) vade
- Copyright (c) Blackhart
- Copyright (c) b01xy


    This package is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This package is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <http://www.gnu.org/licenses/>.
    
    v001 shaders are licensed under the
    Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License.
    https://creativecommons.org/licenses/by-nc-sa/3.0/
