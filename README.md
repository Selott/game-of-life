#Conway's Game of Life
> The Game of Life, also known simply as Life, is a cellular automaton
> devised by the British mathematician John H. Conway in 1970.
> This game does not require players or their input, meaning that its
> evolution is determined by its initial state.

##Rules
* Any live cell with fewer than two live neighbours dies, as if by underpopulation
* Any live cell with two or three live neighbours lives on to the next generation
* Any live cell with more than three live neighbours dies, as if by overpopulation
* Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction

Which can ultimately be shortened down to:

* Any live cell with two or three live neighbours lives
* Any dead cell with three live neighbours becomes a live cell
* All other live cells die in the next generation. Similarly, all other dead cells stay dead

##Patterns
* ![Block](https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Game_of_life_block_with_border.svg/66px-Game_of_life_block_with_border.svg.png)
* ![Beehive](https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Game_of_life_beehive.svg/98px-Game_of_life_beehive.svg.png)
* ![Blinker](https://upload.wikimedia.org/wikipedia/commons/9/95/Game_of_life_blinker.gif)
* ![Heavy-Weight spaceship (HWSS)](https://upload.wikimedia.org/wikipedia/commons/4/4f/Animated_Hwss.gif)

##Technichal details
I will realize Conway's Game of Life in multiple programming langugaes. This allows me to
ultimately become more fluent in many of the globally used ones.
Consider this a learning projects.
This is by no means optimized, but if you want to contribute or optimize it, go ahead and create issues/PR's.


