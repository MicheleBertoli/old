# What is it?

In [Gummy Industries](http://gummyindustries.com), we have a [Skype](http://skype.com) chat where we share many links.

Thanks to this tool, we are able to post them (if they have hashtags) automatically to [Tumblr](http://tumblr.com) (see [http://ooold.tumblr.com](http://ooold.tumblr.com))

# message.lid:
You can create a "message.lid" file in the app root folder containing the message di you want to start from, this file can be found in the Messages table (in the Skype db).
If not created the .lid file will be automatically created using the last available message id.

# Configuration (config.js)

## skype:
### userName:
Your skype user name.
### convo_id:
The conversation id you want to track. You can find it on the Conversations table (in the Skype db).

## tumblr:
You can get your Tumblr tokens here: 
[https://api.tumblr.com/console](https://api.tumblr.com/console)

# How to use it

`node app` or `npm start`.

This script does not contains any running loop, therefore you need to run it once every while (that's why it needs the message.lid trace file)