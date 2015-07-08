# betterbash
## a better shell prompt on [EY Cloud Classic](https://cloud.engineyard.com/)

The default shell prompt on EY Cloud Classic is defined by Amazon with their internal DNS
hostname, yielding something like domU-foo-bar-whatever-idk-this-blows as your hostname. That
just plain sucks and it's useless, so I wrote this to customize PS1 so I know what machine I'm
on in a given cluster at a given time.

It works by creating a .prompt file in a given user's $HOME, then modifying $HOME/.bashrc to
source $HOME/.prompt which assigns the PS1 variable.

### Status: Development

This hasn't been tested a whole lot and there may still be changes down the line, but it's so far
working in my own experimentation. That said, be careful - YMMV.

### License: MIT

Copyright (c) 2015 J. Austin Hughey <jaustinhughey@gmail.com>

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
