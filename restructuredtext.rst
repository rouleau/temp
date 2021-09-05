================
reStructuredText
================

- bullet one
- bullet two

.. tip:: This is a **tip** box.

.. error:: This is an **error** box.

*********************
Chapter
*********************
Section
=====================
Subsection
---------------------
Subsubsection
^^^^^^^^^^^^^^^^^^^^^
Paragraph
~~~~~~~~~~~~~~~~~~~~~

.. csv-table:: Eye colors
   :header: "Name", "Firstname", "eyes"
   :widths: 20, 20, 10

   "von Laszewski", "Gregor", "gray"

`This is a link to an html page <hadoop.html>`_

-a            command-line option "a"
-b file       options can have arguments
              and long descriptions
--long        options can be long also
--input=file  long options can also have
              arguments
/V            DOS/VMS-style options too

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

.. code:: python

  def my_function():
      "just a test"
      print 8/2
      
.. code:: sql

    FOR docs IN ['Test', 'test']
      UPDATE docs {'newVal: 12345}
