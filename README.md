# Live demo

The demo is published on [this page][demo-live-link].

This is the game 2048.
You can use the arrow keys to play (or the touch screen on tablets and mobiles).
Tiles with same number can merge into one that sums the numbers. 
The goal of the play is to sum 2048 on a single tile.

# Highlighted features

## Reusability

This demo demonstrates how you can port existing JavaFx applications.
There was indeed already a [JavaFx version][fx2048-link] of the game, and this demo is just a port of it in WebFx so the game could be transpiled into a web version.

## HTML/CSS mapping

This demo also shows that you can write applications such as games using the scene graph based and CSS (this games is not canvas based).

[demo-live-link]: https://webfx-fx2048-demo.netlify.app
[demo-source-link]: https://github.com/webfx-project/webfx/blob/master/webfx-demos/webfx-demo-enzoclocks/webfx-demo-enzoclocks-application/src/main/java/webfx/demo/enzoclocks/EnzoClocksApplication.java
[fx2048-link]: https://github.com/brunoborges/fx2048