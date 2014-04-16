yay
===

yet another yuv viewer 

---------

yay is a simple viewer for planar 4:2:0 YUV pictures and
sequences. 

One nice thing about yay is that it tries to find width and height
parameters in the path or filename of the yuv file. So if your file is
named something like mobile_352x288.yuv you don't have to specify
width and height.

Optionally you can provide width and height parameters via "-s
<width>x<height>" paramter.


usage:
------

yay [-s <width>x<height>] filename.yuv

keys:
  ->  : next frame
  <-  : prev. frame
 up   : zoom in
down  : zoom out
space : play sequence
   r  : rewind
   g  : toggle grid (16x16)
   q  : quit


Legal stuff
-----------

Copyright (C) 2006 Matthias Wientapper

yay is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation; either version 2 of the License, or (at your
option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307
USA


Thanks to Florian Broekaert for helping me finding some bugs.

Comments are welcome.

        - Matthias Wientapper <m.wientapper@gmx.de>
