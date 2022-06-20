=====================
This Is A New Project
=====================

.. Here is were you specify the content and order of your new book.

.. Each section heading (e.g. "SECTION 1: A Random Section") will be
   a heading in the table of contents. Source files that should be
   generated and included in that section should be placed on individual
   lines, with one line separating the first source filename and the
   :maxdepth: line.

.. Sources can also be included from subfolders of this directory.
   (e.g. "DataStructures/queues.rst").

SECTION 1: Basic text
:::::::::::::::::::::



I LOVE MY GIRLFRIEND SO MUCH AAAAA
----------------------------------
.. mchoice:: test_question2
   :correct: a,b,c,d
   :answer_a: her face
   :answer_b: her body
   :answer_c: her personality
   :answer_d: her uhhh her uh

   what do i love about her?

Section 2: Poopy pants
:::::::::::::::::::::::

.. youtube:: FveF-we6lcE

Runestone uses the ``restructuredText`` (rst) markup language.  We chose this over markdown largely because rst is extensible.  Nearly all of the basic markup tasks are already handled by restructuredText.  You should check out the docs for the basics of restructuredText (link below). Our extensions are all for the interactive elements.  One key hint about restructuredText:  Its like **Python** -- *indentation matters!*

* `restructuredText Docs <http://docutils.sourceforge.net/rst.html>`_
* `Runestone Docs <https://runestone.academy/runestone/static/authorguide/index.html>`_
* Join the discussion on our `Google Group <https://groups.google.com/forum/#!forum/runestone_instructors>`_
* Tell us about problems on `Github <https://github.com/RunestoneInteractive/RunestoneComponents>`_



SECTION 3: Testing multiple choice answers
::::::::::::::::::::::::::::::::::::::::::

Testing with a weird question
-----------------------------

.. mchoice:: test_question1
   :correct: a
   :answer_a: yes
   :answer_b: no
   :feedback_a: uh oh! Stinky!!!
   :feedback_b: IT IS STINKY!!


   Is pant poopy?


Section 4: codelens
:::::::::::::::::::


.. codelens:: test_code1

    print("uh oh!")
    :question: try it yourself!
