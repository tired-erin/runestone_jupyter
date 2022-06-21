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



This is another test question with multiple correct
---------------------------------------------------
.. mchoice:: test_question2
   :correct: a,b,c,d
   :answer_a: this is right
   :answer_b: this too!
   :answer_c: hopefull this as well
   :answer_d: and finally this!

   Test question

Section 2: Testing YT with a video
::::::::::::::::::::::::::::::::::

.. youtube:: FveF-we6lcE




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

Testing codelens

.. codelens:: test_code1

    print("uh oh!")
    :question: try it yourself!
