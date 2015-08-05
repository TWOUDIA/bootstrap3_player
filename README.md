bootstrap3_player
================

An HTML5 Audio Player Skin For Twitter Bootstrap 3

#### Requires:

  * Twitter Bootstrap 3 - http://twitter.github.com/bootstrap/
  * jQuery - http://jquery.com/

#### How to use

Clone or download this repo; then open the included [`index.html`](index.html) file: 
-  with **your browser** to:  
    -  see a live demo on your local machine 
    -  compare it with the [screenshots or live demo](#screenshots) below
- with your [text editor](index.html) to:
    -  see all the css and js files you need to link to
    -  see the `<audio>`  tags in use

#### Styling caveat

Works best when the player is not enclosed in too narrow a container in your page otherwise the player controls can appear jumbled. Both the seek and volume sliders are hidden on narrow (xs) viewports. A good strategy is to start "mobile-first" as usual by enclosing your audio block in a row that uses all twelve grid colums of the page's outer container in an xs viewport. Then, on wider viewports, the player can occupy fewer of the page's grid columns. See the example row widths in  [`index.html`](index.html) and the corresponding [live demo](http://yannicklin.net/razor/GitHub-bootstrap-player.php).   

##### Forked from IainHouston's [bootstrap3-player] (https://github.com/iainhouston/bootstrap3_player), which also forked from William Randol's [bootstrap-player](https://github.com/WilliamRandol/bootstrap-player)

 -  `bootstrap-player` is great for Bootstrap 2
 -  All the functionality of William Randol's player is preserved
 -  `bootstrap3_player` updates the styling of `bootstrap-player`; has fewer dependencies; uses Bootstrap 3

#### <a name="screenshots">Screenshots and Live demo

[See a live demo](http://yannicklin.net/razor/GitHub-bootstrap-player.php)

-  Audio with no additional data ![](screenshots/demo1.png?raw=true)

-  Audio with data - collapsed ![](screenshots/demo2.png?raw=true)

-  Audio with data - expanded ![](screenshots/demo3.png?raw=true)

#### Existing Bugs

-  button icon rolled back to "PLAY" while changed the playing position of song (27 JUL 2015)

