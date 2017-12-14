# README

## Game Engines and Game Sound Techniques lessons (Dec 2017)

These are the slides for the _GE & GST_ lessons. Build with [reveal.js](https://github.com/hakimel/reveal.js).

For more information:
[limulo.net](http://www.limulo.net/)
[GE & GST homepage](https://limulo.github.io/game-sound-sae2017/)

## Installation

In order to run this presentation you first need to install _NodeJs_: follow the instructions you find [here](http://www.limulo.net/wiki/index.php?title=Reveal.js) to do that.

Then you must clone this repo, go inside its folder and:
* install all the necessary _modules_ with `npm install`;
* start the presentation with `npm start`.

## Add content to the presentation

In order to add new content to the presentation do one of the following operations:

1. Edit the `index.html` file taking care of special _data separator_;
2. Edit the corresponding `.md` files inside the `_slides` folder;
3. Add new images inside the `_images` folder or link them from the [GE & GST](https://github.com/Limulo/game-sound-sae2017) repo;
4. Do the same with other kind of resources you may need (like sounds, videos, gif and so on).

There's no need to modify anything else.

## Add styles to the presentation

Follow the instruction you find [here](https://github.com/hakimel/reveal.js#instructions):
* [slide background](https://github.com/hakimel/reveal.js#slide-backgrounds);

## Notes

The _iframe_ background will not work if you are using a video starting from a specific point in time:
* both this vesrion _?t=2m18s_;
* or this one _?start=123_;

## Deploy the presentation to GitHub pages

Follow the instruction found on these links:
* Angelo Basile [post](http://anbasile.github.io/programming/2015/12/25/hosting-reveal-pres-on-github/). You will also need **pandoc** along with **reveal.js** in order to convert your _.md_ files into _.html_; 
* Also read [this](http://pandoc.org/MANUAL.html#producing-slide-shows-with-pandoc) page from the **pandoc** on--line manual. It should be very useful.

