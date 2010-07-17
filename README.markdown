NSTreeController Tutorial
=========================

This repository contains a tutorial for using NSTreeController in Mac OS X 10.5 and later. The tutorial itself is an HTML file. There also is source code to get you started. The initial version came from [Keith Blount’s  “NSTreeControllerTutorial”][1] which is available from his [Literature and Latte - Free Stuff][2] page. I (Jan Weiß) updated it for 10.5 and rewrote parts. 

This currently is a first draft of the changes that are necessary to use the API updated in 10.5. Some of the changes I made are pretty crude, but better to get it out there. Please feel free to fork it and make any corrections or fix bugs. You can then send me a pull request if you like.

The main change I made initially was using 10.5’s NSTreeNode public method -representedObject instead of 10.4’s _NSArrayControllerTreeNode private method -observedObject. 

You should be able to follow the tutorial up to the point where the drag’n’drop code is added towards the end of the tutorial. That code didn’t work for me. A completed, working version can be found in the [CoolOutliner repository][3]. 

License
-------

Copyright (c) 2010, Jan Weiß (github@geheimwerk.de)  
All rights reserved. 

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

- Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

  [1]: http://www.literatureandlatte.com/freestuff/NSTreeControllerTutorial.zip
  [2]: http://www.literatureandlatte.com/freestuff/index.html
  [3]: http://github.com/JanX2/CoolOutliner
