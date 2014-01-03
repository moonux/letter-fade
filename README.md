LetterFade.js
==========

LetterFade is a jQuery plugin that gradually fades individual letters in a piece of text one-by-one in random order until the entire text is either transparent or opaque.

Dependencies
-------------------
* jQuery

Examples
-------------

  $('#fade-me-out').letterFade(); // fade-out by default
  $('#fade-me-in').letterFade({ fade: 'in' });

  $('#example').letterFade({
    fade: 'in',   // fade letters 'in' or 'out'
    duration: 500,  // how long the fade lasts per-letter
    delay: 250    // how long to wait between letters
  }, function() {
    // run this callback when the effect is complete
  });

The effect should be applied on document text that contains no children elements.

Demo
--------
The effect can be seen here: [http://servomakes.com](http://servomakes.com)

Author
---------
(c) 2014 Moon Lee, Codeflow LLC

License
----------
MIT License

[http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)