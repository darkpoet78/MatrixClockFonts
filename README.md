# MatrixClock Fonts
Fonts to be used with LED Matrix Clocks

## About these fonts
These fonts are designed strictly with LED Matrix Clocks in mind, especially a unit that uses [EsphoMaTrix](https://github.com/lubeda/EsphoMaTrix/). They are BDF Fonts, so they can be directly implemented with ESPHome (and perhaps Arduino).

Because BDF fonts are bitmap fonts, the size of these fonts is pixel-fixed. They are not resizable like TTF fonts.

Most characters will be 3 pixels wide, but certain characters like G and M and & are wider. Punctuation characters are generally 1 or 2 pixels wide.  All characters have 1 empty column on the right side... except the space itself, which is only 1 column wide. This should help when you need a bit of space between characters but don't want to lose 4-5 columns of pixels while doing so!

The number of characters has been extremely reduced to save flash memory.  Sorry to the European languages but accents on letters only 5 pixels tall are nearly impossible to recognize anyway.

Fonts will be added as I continue work on this project.

## 6-Series Fonts
Suitable when using a weekday band underneath the time on an 8-row matrix.

### MatrixClock-Chunky6
![image](./MatrixClock-Chunky6.png)

[Download](./MatrixClock-Chunky6.bsd)

## 8-Series Fonts
Suitable when using the full height of an 8-row matrix.

### Coming Soon

## Authorship
```
** The original 3x5 font is licensed under the 3-clause BSD license:
**
** Copyright 1999 Brian J. Swetland
** Copyright 1999 Vassilii Khachaturov
** Portions (of vt100.c/vt100.h) copyright Dan Marks
**
** All rights reserved.
**
** Redistribution and use in source and binary forms, with or without
** modification, are permitted provided that the following conditions
** are met:
** 1. Redistributions of source code must retain the above copyright
**    notice, this list of conditions, and the following disclaimer.
** 2. Redistributions in binary form must reproduce the above copyright
**    notice, this list of conditions, and the following disclaimer in the
**    documentation and/or other materials provided with the distribution.
** 3. The name of the authors may not be used to endorse or promote products
**    derived from this software without specific prior written permission.
**
** THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR
** IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
** OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
** IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT,
** INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
** NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
** DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
** THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
** (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
** THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
Modifications to Tom Thumb for improved readability are from Robey Pointer, see this page for the BDF file which I used as a base:  http://robey.lag.net/2010/01/23/tiny-monospace-font.html

The original author does not have any objection to relicensing of Robey Pointer's modifications (in this file) in a more permissive license.  See the discussion at the above blog, and also here: http://opengameart.org/forumtopic/how-to-submit-art-using-the-3-clause-bsd-license

As such, these fonts are released under the CC-BY License: https://creativecommons.org/licenses/by/4.0/