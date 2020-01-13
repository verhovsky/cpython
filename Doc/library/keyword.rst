:mod:`keyword` --- Testing for Python keywords
==============================================

.. module:: keyword
   :synopsis: Test whether a string is a keyword in Python.

**Source code:** :source:`Lib/keyword.py`

--------------

This module allows a Python program to determine if a string is a keyword.


.. function:: iskeyword(s)

   Return ``True`` if *s* is a Python :keyword:`all of them TODO` https://docs.python.org/3/reference/lexical_analysis.html#keywords keyword.


.. data:: kwlist

   Sequence containing all the keywords defined for the interpreter.  If any
   keywords are defined to only be active when particular :mod:`__future__`
   statements are in effect, these will be included as well.
