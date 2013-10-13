Libpydoc
========

A alternative implementation of pydoc's internals aiming to decouple the logic and display portions.

Note: This is a work in progress.

Why?
----
Pydoc has a couple of different output formats, however they're tightly coupled to the logic that generates the information. While working on Classify I found some very useful inspection functions in pydoc but had to build my own internal structure to describe the class.

Example presentation layers:
* `Classify<http://pypi.python.org/pypi/classify>`_
* `Classy Class Based Views<http://ccbv.co.uk>`_


Python objects to cover
-----------------------
* Class
* Method
* Function
* Built-in
* Check pydoc for more
