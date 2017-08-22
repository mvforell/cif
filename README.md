__cif__
=======

Custom Image Format specification and reference implementation
--------------------------------------------------------------
*Note:* This is in a very early stage of development and not actually meant to be used productively but to learn a thing or two about (custom) file formats and compression.

Dependencies
------------
The reference implementation uses tkinter and [py-lz4framed](https://github.com/Iotic-Labs/py-lz4framed).

Usage
-----
Customize (optional) and run __*create_sample.py*__, which will create a .cif file you can display using __*display.py*__.

Future of this project
----------------------
As said in the specification, an alpha channel may be implemented. Also, the reference implementation does not check the image width, height or comment size, which never is a good idea and the generated sample image could probably be improved.
