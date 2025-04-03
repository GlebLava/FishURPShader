The graph is set to use some instancing related code that is not included.
To get it to work:
- replace all **GetSpeedControllInstanced** with an input float. This controls the speed of the swimming animation
- replace all **GetTimeInstanced** with an input float or a delta time node. This drives all the sin waves. 
