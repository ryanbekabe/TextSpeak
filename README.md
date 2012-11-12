TextSpeak
===========

Simple text-to-speech program, uses the Google Translate online service.
Since the public Google TTS only supports text up to 100 characters, the text
is divided into smaller chunks and the resulting MP3 files are merged.
Tested under Windows: in XP audio chunks can be played as they are received,
in Vista and 7 audio is set to play when all has been downloaded because
wx.MediaCtrl fires state change events unreliably there.


Dependencies
------------

TextSpeak requires Python 2.6+ and wxPython 2.8+ (http://wxpython.org/).


Attribution
-----------

Idea and text parsing from
http://glowingpython.blogspot.com/2012/11/text-to-speech-with-correct-intonation.html.


License
-------

(The MIT License)

Copyright (C) 2012 by Erki Suurjaak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
