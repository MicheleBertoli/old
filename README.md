# What is it?

In [Gummy Industries](http://gummyindustries.com), we have a [Skype](http://skype.com) chat where we share many links.

Thanks to this tool, we are able to post them (if they have hashtags) automatically to [Tumblr](http://tumblr.com) (see [http://ooold.tumblr.com](http://ooold.tumblr.com))

# message.lid:

You can create a "message.lid" file in the app root folder containing the message id you want to start from, the id can be found in the Messages table (in the Skype db).
If not exists, the .lid file will be automatically created using the last available message id.

# Configuration (config.js)

## skype:
### userName:
Your Skype user name.
### convo_id:
The conversation id you want to track. You can find it on the Conversations table (in the Skype db).

## tumblr:
You can get your Tumblr tokens here: 
[https://api.tumblr.com/console](https://api.tumblr.com/console)

# How to use it

`node app` or `npm start`.
This script does not contains any running loop, therefore you need to run it once every while (that's why it needs the message.lid trace file).

# LICENSE - "MIT License"

Copyright (c) 2013 Gummy Industries (@gummyindustries)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.