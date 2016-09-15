# Squashing Python bugs

Load the script into Python with the debugging module

	python3 -m pdb name-of-script.py

Add session of temporary breaks with,

	b lineno
	tbreak lineno

List breakpoints, and remove one,

	b
	cl lineno

Advance forward line by line,

	n -or- s

Advance forward to the next breakpoint

	c
