# Final Project Assignment 2: Explore One More! (FP2) 

### My Library: rsound

For my Exporation 2, I decided to delve into the popular audio library rsound.  The documentation is good and it seems to be in popular use because I found various resources to help me start out.

I am in the process in joining a group that is looking to use rsound as a library.  I had one of those members pull me up to speed on how to use the basics of rsound.  He created a simple racket code play a series of piano tones.  Using this, I wanted to try and explore how to make a keyboard piano.

I found a thread on stackoverflow that demonstrated keypress events:
http://stackoverflow.com/questions/14540119/on-key-in-racket

Using this, I simply linked it to the notes to be played.  Here is the resulting code.
<a href="http://imgur.com/S99dlLf"><img src="http://i.imgur.com/S99dlLf.png" title="source: imgur.com" /></a>

There are some issues with this keypress.  If I quickly press a lot of keys or a lot of keys at the same time, the sound buffer gets overloaded quickly and potentially crashes the code.  it might be a problem with rsound but this is something worht investigating.

Learning how to keypress fits very well with what I wanted to do with FP1.  In FP1, I wanted to rotate my cube with the arrow keys.  I can go back and explore how to do that now.  But moving ahead, I want to see if i can make a simple visual with my keyboard piano.  Whenever a key is pressed, inside a window, a colored box will show up.  Each note will have its own color and it will fade out when released.

I also feel that the group is leaning towards a graphic visualization of sound or some sort.  So this will be interesting!
