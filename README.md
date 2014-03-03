# The Automataic Gardener
A little meditation on embodiment, change, and time inspired by
[Conway's Game of Life.](http://en.wikipedia.org/wiki/Conway's_Game_of_Life)

[Live Demo](http://lharding.github.io/automataic-gardner-js/auto.html)

You are a gardener planting seeds. You have 32 seeds and are trying to grow as many
plants as you can. You plant the first seven seeds during the winter when nothing grows
or dies. When you plant the eighth seed, the growing season begins, and the seeds grow
into plants that spread and eventually die. Once you've planted all your seeds and
the last plant dies, the growing season ends.

The rules that determine whether a seed grows or dies are the same as Conway's Game of Life:

* Any live plant with fewer than two live neighbors dies, as if caused by under-population.
* Any live plant with two or three live neighbors lives on to the next generation.
* Any live plant with more than three live neighbors dies, as if by overcrowding.
* Any dead plant with exactly three live neighbors becomes a live cell, as if by reproduction.
* Additionally, when there is too much activity in a space, it gets overcultivated, and the ground turns increasingly darker shades of gray. Ground that becomes extremely overcultivated can no longer support life.

