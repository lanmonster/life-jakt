# Conway's Game of Life - Jakt
This is an implementation of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in jakt using SDL2 to draw to the screen.

## Compile and run
1. Clone and build [jakt](https://github.com/SerenityOS/jakt) 
2. Install SDL2 for your platform (out of scope for this readme).
3. `jakt main.jakt -l SDL2  -I /usr/local/Cellar/sdl2/2.28.1/include/SDL2 -L /usr/local/Cellar/sdl2/2.28.1/lib -O -o life`
4. `build/life`

## Usage
`Tab` starts and stops the simulation.  
`Spacebar` stops the simulation and puts you into "Selection Mode".  
In "Selection Mode", you can move the selection with the arrow keys and toggle a cell with `Enter`.  

## Config
In `config.jakt` there are some things you can change based on your liking.  
If there is not a predefined color you like, you can use `Color::custom(r, g, b, a)`.

## Acknowledgements
The SDL2 jakt implementation was heavily inspired (read taken from) JT's [jaktnesmonster](https://github.com/jntrnr/jaktnesmonster)