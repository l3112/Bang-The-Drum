# Bang-The-Drum
From Wes Bos 30 JavaScript challenge
Building a JavaScript portfolio
data attributes (data-___) data key to data key  audio (find audio and play it, find div so it can animate itself)

line 61 - we’re listening for an event.
the code won’t have any reaction on the screen, but in the console it will.

audio.current time =0; rewinds it back to the beginning so you can wail on the buttons like a madman

audio.play(); plays the noises

in css, see transition:all, which scales up the border color. You can put a timeout in both the html and css, but they may go out of sync.

I changed my colors to hexidecimal code #afcd38

in the remove transition function (

if(e.propertyName !== 'transform') return;

this.classList.remove('playing'); 

)

When you go to Elements, to the keys div class, and press a corresponding letter, you can very quickly see the classes change.

If you press and hold the corresponding buttons, you can get the animation stuck in permanent ‘on’ mode.
