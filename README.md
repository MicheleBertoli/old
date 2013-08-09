# What is it?

In [Gummy Industries](http://gummyindustries.com), we have a [Skype](http://skype.com) chat where we share many links.

Thanks to this tool, we are able to post them (if they have hashtags) automatically to [Tumblr](http://tumblr.com) (see [http://ooold.tumblr.com](http://ooold.tumblr.com))

# Configuration (config.js)

## file:
You must fill a text file with the last Skype message id.
You can find it on the Messages table (of the Skype db).

## skype:
### db:
Replace %SYSTEM_USER% with your System user and %SKYPE_USER% with your Skype user.
### convo_id:
The conversation you want to track. You can find it on the Conversations table (of the Skype db).

## tumblr:
You can get your Tumblr tokens here: 
[https://api.tumblr.com/console](https://api.tumblr.com/console)

# How to use

`node app`
