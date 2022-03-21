# Pong

### Scope
- [ ] Draw Shapes 
- [ ] Control 2d positions
- [ ] Collision detections between particles and map
- [ ] Sound effects and interactivity
- [ ] Score counting 

### pong-0

- love.load() -> used for initializing our game state at the beginning of the program.
	- It is a start up function,
- love.update(dt) -> variable dt is passed through a function which will be elapsed (in seconds) since the last frame.
	- can be used to scale any changes in our game for behavior across frame-rates. 
- love.draw() -> drawing and rendering behavior. 
- love.graphics.printf(text, x, y, [width], [align]) -> for drawing the contents into the screen. 
- love.window.setMode(width, height, params) -> initialize the windows dimensions and parameters like vsync. 

### pong-1 -> low res update

-love.graphics.setDefaultFilter()