These are the popmenu scripts and macro definitions I use for City of Heroes: Homecoming.
They're mostly to make creating new alt characters simpler, as I can just run /popmenu setup
a few times to generate clicky buttons and stuff.

A few other tips:

Once you have your windows, chat channels, etc all configured the way you like them,
do the following commands:
```
  /wdwsave
  /optionsave
  /bindsave
  /chatsave
```
This saves your setup over the default, and it will become the new default for new characters.

However, chat channels themselves are not restored, so you will need to load that back in via
/chatload, which is done by my popmenu setup generic option as well.  The four commands match,
so you can do:
```
  /wdwload
  /optionload
  /bindload
  /chatload
```
Finally, your window color will be whatever alignment you were when you saved the default, so
to change it to match your new character -- or just to be different:
```
  /window_color 36 145 255 216 for hero
  /window_color 166 41 41 216 for villain
  /window_color 112 112 114 216 for praetorian
```
Obviously you can put any values you like there, so feel free to have a pink or purple UI!

Have fun!
