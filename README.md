# About
easy_draw is an experimental library for drawing 2D and 3D environments. This is still very early
and experimental.

easy_draw is split across a few different sub-libraries:
 - easy_2d - for drawing 2D environments. No dependencies.
 - easy_3d - for drawing 3D environments. Depends on easy_mtl.
 - easy_mtl - for handling programmatic materials.


---
# easy_mtl
easy_mtl is an experimental library for parsing assembly-like, programmable material files and generating
shader code from those materials for use in 3D graphics APIs such as OpenGL. The main goal is to experiment
with the idea of having materials defined programmatically as a series of instructions, as opposed to
static materials which are just made up of pre-defined variables.


---
# License
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>