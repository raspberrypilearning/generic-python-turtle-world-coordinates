You can set the coordinates of the Python turtle screen if you want to use different ranges. 

Normally, the centre of the screen is (0,0). To just use positive coordinates you can use:

```python
screen = turtle.Screen()
screen.setup(600, 400)
screen.setworldcoordinates(0, 0, 600, 400) # (start_x, start_y, end_x, end_y)
```

The first two inputs for `setworldcoordinates` are the x and y coordinates for the bottom left corner of the screen. The second two inputs are the x and y coordinates for the top right of the screen. 

Example:
<iframe src="https://trinket.io/embed/python/7800e0a83b?start=result" width="100%" height="450" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>