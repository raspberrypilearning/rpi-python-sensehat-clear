- The LEDs on the Sense Hat matrix can be cleared, to remove any text, letter or images you may have displayed. The Sense Hat Python module first needs importing, and a `sense` object needs creating.

	```python
	from sense_hat import SenseHat
	sense = SenseHat()
	```

- Now the screen can be cleared:

	```python
	sense.clear()
	```
- This clears the matrix by turning off all the LEDs. You can pass a colour into the `clear()` function, to clear the matrix with any specific colour.

	```python
	red = (255, 0, 0)
	sense.clear(red)
	```
