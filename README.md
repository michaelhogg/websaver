WebSaver: A WebKit-based Mac OS X screensaver
=============================================

A Mac OS X screensaver which simply embeds WebKit to display a webpage or JavaScript application. Perfect for Canvas animations.

You can specify a web url as screen saver.

This version includes a simple Preferences sheet.

WebGL is supported (thanks to [cggaurav](https://github.com/cggaurav/WebSaver/commit/84447cd)).

Instructions
------------

1. Open **WebSaver.xcodeproj** in Xcode.

2. Select **Build** in the **Product** menu. **WebSaver.saver** will be created at:

        /Users/.../Library/Developer/Xcode/DerivedData/WebSaver-.../Build/Products/Debug/WebSaver.saver

3. Double-click **WebSaver.saver** to automatically install into System Preferences.

Occasionally, a screen saver won't work when installed automatically (this [issue](http://lists.apple.com/archives/cocoa-dev/2006/Oct/msg00936.html) has existed in OS X for years).

To perform a manual installation, copy **WebSaver.saver** to:

    /Users/.../Library/Screen Savers/

Notes
-----

* Change the "Product Name" in the "Web" target if you are distributing a screensaver to prevent conflicts with others.
* thumbnail.png – 90 x 58 pixels | thumbnail@2x.png – 180 x 116 pixels

License
-------

Copyright (c) 2013, Thomas Robinson <http://tlrobinson.net/>

Copyright (c) 2012, Senseg Ltd <http://www.senseg.com>

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.
    * Neither the name of the Thomas Robinson, Senseg nor the
      names of its contributors may be used to endorse or promote products
      derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY Thomas Robinson AND/OR Senseg ''AS IS'' AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL Thomas Robinson BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
