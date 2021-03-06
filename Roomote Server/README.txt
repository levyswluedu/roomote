Roomote Server

Copyright 2010-2011 Brian Pratt. All rights reserved.

This software is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public
License as published by the Free Software Foundation; either
version 3 of the License, or (at your option) any later version.

This software is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General
Public License along with this library; if not, write to the
Free Software Foundation, Inc., 59 Temple Place, Suite 330,
Boston, MA  02111-1307  USA

--------------------------------------------------------------------------------

This software is provided "as is," and you use the software at your own risk.

Brian Pratt makes no warranties as to performance, merchantability, fitness for a particular purpose, or any other warranties whether expressed or implied.

No oral or written communication from or information provided by Brian Pratt shall create a warranty.

Under no circumstances shall Brian Pratt be liable for direct, indirect, special, incidental, or consequential damages resulting from the use, misuse, or inability to use this software, even if Brian Pratt has been advised of the possibility of such damages.

--------------------------------------------------------------------------------

Roomote Server is my first OS X application. Please be kind :-)

Roomote Server is an intermediary between the Roomote iPhone app and a Roomba (or Create) robot. Its main function is to relay commands from the Roomote to the Roomba.

To make the Songs and Demos work, you will have to run the "macosx_setup.command" file:
 - Open a Terminal window (/Applications/Utilities/Terminal)
 - Drag the macosx_setup.command file into the window
 - Press the "return" key
 - Type in your password (assuming you have an administrator account)
You should only have to do this once.


For communication with the Roomba, I have included C libraries made available by Tod E. Kurt. I have also included the Java RoombaComm project for running demos with the Roomba and for playing RTTTL-formatted songs. Both of these projects are available in source form under the GPL.
The source was obtained from http://www.dprg.org/projects/2009-07a/ (http://svn.dprg.org/viewvc/roomba/)

You are free to make modifications and redistribute the software under the terms of the GPL.

I especially encourage anyone to make a Windows version of this software. I'm sure that a totally Java version of the Roomote Server could be done that would be cross-platform. I initially created this project just to experiment with coding on the Mac OS X platform and don't have enough time or interest to rewrite the project for other platforms. I would be happy to help someone else's efforts, though. Feel free to contact me at roomote 'at` brianhpratt `dot' net. I will happy link to your Windows/Linux port from http://www.brianhpratt.net/Roomote/ as well.