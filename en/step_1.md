The LEDs of the Sense HAT matrix can be cleared to remove any text, letter, or images you have displayed.

- First, you need to import the `Sense HAT` Python module and create a `sense` object.

	```python
	from sense_hat import SenseHat
	sense = SenseHat()
	```

- Now you can clear the screen:

	```python
	sense.clear()
	```
- This clears the matrix by turning off all the LEDs. You can also pass a colour into the `clear()` function to clear the matrix with a specific colour.

	```python
	red = (255, 0, 0)
	sense.clear(red)
	```
