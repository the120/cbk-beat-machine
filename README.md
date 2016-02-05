# Beat Machine!

## Notes...

Some inspirational machines:

- **Patatap -- http://www.patatap.com/**

  A beautiful sound maker -- visually and aurally. A minimal version is not
  too difficult, but still introduces a number of JS and audio concepts.
  
- **HTML5 Drum Machine -- http://www.html5drummachine.com/**
  
  This one is great in that it would let the students do more, like saving 
  their beats, etc. However, it's also a more complicated project. It might 
  make sense to start with a Patatap-like project, since it's relatively 
  simple, but still introducing many concepts they'll need for a full beat 
  machine.
  
  A similar timing-based (but *much more beautiful*) example is Tone Matrix
  (http://tonematrix.audiotool.com/). Also, you can share, which is
  [awesome](https://tonematrix.audiotool.com/_/0.0.830.og0.gg0.s0g.60g.20g.228.8.o8.dg.30.0.g0.g0):

- **typedrummer -- http://typedrummer.com/**
  
  A bit of a hybrid between *Drum Machine* and *Patatap*. Use keys to build a
  beat, but then that sequence becomes a pattern that's repeated continuously.
  Maybe makes sense as a second step, between *Patatap* and *Drum Machine*.
  
So, what does our *Patatap* look like?

------------------------------------------------------------

Should we have the kids provide some sort of prompts or instructions to the
user? Yes. It would be a good exercise in thinking from the perspective of the
user.

------------------------------------------------------------

We should have some visual feedback (like *Patatap*) on key presses. It can be
driven by CSS transformations. Here's a codepen where we were playing with some
CSS transitions: http://codepen.io/mjumbewu/pen/eJKeBq. It might be good to have
the kids play around in a code pen like that when we get there.

------------------------------------------------------------

We should try to introduce little systematic errors (like leaving dashes out of
ID names in one place but not another) so that we can practice debugging with
the students as well.

------------------------------------------------------------

We can have two to three steps in the first phase of this project (the Patatap phase):

1. **Step I**
   Start with a button on the page, and a sound-playing function. Have the
   students write code to make the page play a sound when the user clicks the
   button. Have the students add more buttons and sounds to make sure they
   understand variables and calling functions.
   
2. **Step II**
   With several buttons playing several different sounds, start to respond to
   key presses instead. Hook up each button/sound to a different key. Work
   through finding what the key code is for any given key, and then using that
   key code from the event object.
   
3. **Step III**
   Now that each sound is mapped to a given key, start making the layout a
   little more fancy. Students should be getting more comfortable with the
   difference between IDs and classes on elements. Start getting into more
   complex understandings of classes and selectors.
