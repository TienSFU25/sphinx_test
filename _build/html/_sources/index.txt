.. Tien's Sphinx Docs documentation master file, created by
   sphinx-quickstart on Sun Apr  5 11:54:08 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Tien's Sphinx Docs's documentation!
==============================================

Contents:

.. toctree::
   :maxdepth: 2
   :numbered:
   :titlesonly:

   Hello<linked>



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

:ref:*emphasis*
:ref:**boldface**
:ref:``some code sample``

* This is a bulleted list
* It has two items, the second
	item uses two lines

1. This is a list
2. This goes with the above item

#. Another list
#. With #

* parent
* parent
	
	* child
	* child

* parent

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

| These lines
| are broken just like
| in the source file.


This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.


+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+



=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======



Go to Google `google_link`_.

.. _google_link: http://www.google.ca/


############
Parts
############

********
Chapters
********

Sections
========

.. function:: foo(x)
              foo(y, z)
   :module: some.module.name

   Return a line of text input from the user.

.. image:: mona_lisa.png

.. _my-reference-label:

Section to cross-reference
==========================

This is the text of the section.

It refers to the section itself, see :ref:`my-reference-label`.

:doc:`Hello </linked>`


Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_


.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.