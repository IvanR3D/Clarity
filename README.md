Clarity

=======

  

A simple, customisable and scriptable platform game engine.

See it in action here: https://ivanr3d.com/games/clarity/
Or edit here: https://codepen.io/ivanr3d/pen/mdzddwN

All map data is contained within the "map" variable in index.html, you can add new maps by making different map variables and loading them via an activated script as demonstrated. You can activate any script you want when a certain tile is entered, there are countless possibilities such as colour activated gates, teleportation, loading new maps, activating traps, and killing the player. It's limited to your imagination, so get creative.

Have a look at the comments in the map variable to understand how it works.


## What's new in this fork?

 - Added map-generator.html. A simple webpage that will allow you to generate a table to paint your own map. Then generate a map array that you can load in the main page (index.html)
 - The index.html was modified to allow to load new maps with a button.

## Roadmap to improve this fork
In case you want to contribute in the future of this fork, here are some ideas  I want to implement soon. You can add your own using the issues section.
 - **Maps collection**. An index with different maps to play.
 - **Map editor.** An option in the map-generator.html that allow the user to introduce a map array and then edit it.
 - **Arrow buttons.** To have the possibility of playing on smartphones and tablet.
 - **Mobile friendly.** Improve the styles of the files to make it easier to use on mobile. 
 - **Map generator enhancement.** Make the experience of creating new maps faster.

## Known issues
There is a problem to edit the original map because the option to edit map in the [map builder](https://ivanr3d.com/games/clarity/map-builder.html) do not support editing a map with different sizes of rows or columns. For example: if a row has 13 cells but other have more or less than that, the recreation of the map will go wrong.

## Credits
Thanks to the original creator for such a great game platform engine!
https://github.com/dissimulate/Clarity
