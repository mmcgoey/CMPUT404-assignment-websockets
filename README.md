CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program


CITATIONS/ EXTERNAL SOURCE CODE
========================
IMPORTANT EXTERNAL CODE USED:
I used code from Abram Hindles chat.py and broadcaster.py provided to us in the CMPUT 404 class notes.
I used some of the code from chat.py for my sockets.py program
The code was taken from this repository in the chat.py and broadcaster.py programs
https://github.com/uofa-cmput404/cmput404-slides/tree/master/examples/WebSocketsExamples

Specifically I used the Client class, the read_ws, subscribe_socket, send_all, and send_all_json methods with slight modifications to update the world

I also reused some code from my assignment 4 submission linked here https://github.com/mmcgoey/CMPUT404-assignment-ajax
Specifically I reused the update, world, get_entity, clear functions from my assignment 4 submission for sockets.py
I also reused some of the code I wrote in the update() function in assignment 4 for getting the world using xmlhttp get

Citations: 
The only other resouce I referred to was this website https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_client_applications

Prereqs
=======
Create a virtual environment and install the required dependencies.

```bash
virtualenv venv --python=python3
source venv/bin/activate
pip install -r requirements.txt
```
Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle and Mark McGoey.

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2022, Sylvain Hellegouarch, Abram Hindle, Mark McGoey
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

 * Redistributions of source code must retain the above copyright notice,
   this list of conditions and the following disclaimer.
 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
 * Neither the name of ws4py nor the names of its contributors may be used
   to endorse or promote products derived from this software without
   specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

Contributors
============

* Mark Galloway
* Abram Hindle
* Cole Mackenzie
* Mark McGoey
