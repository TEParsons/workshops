
.. ifslides::

  .. image:: /_static/OST600.png
    :align: left
    :scale: 25%

.. _introduction3days:

Introductions
----------------

About us
==========

**Jon Peirce:**
    * Vision scientist at University of Nottingham, UK
    * Principal creator/maintainer of PsychoPy

**Credits:**
    - many other people have contributed to the PsychoPy project (Jeremy Gray, Mike MacAskill, Richard Höchenberger, Sol Simpson being the biggest contributors)

    - Nottingham University have been paying Jons salary while PsychoPy was written

    - Wellcome Trust recently gave us a grant to improve this a LOT

.. image:: /_static/nott_logo.png
    :align: right
    :scale: 25%

The growing team
==========

**Alain Pitiot**
    * All things Pavlovia
**Todd Parsons**  
    * Python developer
**Thomas Pronk and Sotiri Bakagiannis**
    * JS developers
**Rebecca Hirst** 
    * Science officer (and postdoc)

About the workshop
~~~~~~~~~~~~~~~~~~~~~~

Not aiming to teach you all of PsychoPy

Hopefully give you some ideas about what's possible



Getting to know PsychoPy
============================

What is PsychoPy?
~~~~~~~~~~~~~~~~~~

It's `Psychology software in Python`

PsychoPy is several things:
    * a library for use in Python scripts
    * an editor including Python to edit scripts
    * an application with a graphical user interface (GUI) for building experiments

It's, itself, entirely written in Python

Goal of PsychoPy
~~~~~~~~~~~~~~~~~~

The aim is to enable scientists to run as wide a range of experiments as possible, as easily
as possible, with standard computer hardware.

A single piece of software:
    - precise enough for psychophysics
    - intuitive enough for undergraduate psychology
    - flexible enough for everything else
    - capable of running studies in the lab or online

Choice of interface
~~~~~~~~~~~~~~~~~~~~~

It's hard to make something easy enough for undergrads and novices but flexible enough for everything else.

PsychoPy provides two main options, for programmers and non-programmers, but there are also ways to combine the two.

PsychoPy is written in the Python programming language

.. nextslide::

.. figure:: /_images/coderView2020.png

   The Coder view is used to create experiments from Python scripts

.. nextslide::

.. figure:: /_images/builderView2020.png

   The Builder view is used to create experiments visually

Why do people *Code*?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. rst-class:: build

    - To implement more complex experimental designs/procedures(?)
    - To break out of the current trial structure or hardware drawing loop cycle
    - To know exactly what the code is doing(?)
    - To program things that aren't psychology experiments. (e.g. stats, simulations, analyses etc.)

Why do people *Build*?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. rst-class:: build

    - It is far faster to develop experiments!
    - You can still understand (and build on) your experiment next year
    - You'll probably have fewer bugs
    - Code Components can be used in nearly all places where Builder isn't enough
    - Your Builder experiment will also compile to a web (JS/HTML) experiment!

What do **we** do?
~~~~~~~~~~~~~~~~~~~~~~~~~~

I (Becca) and Jon still use both Builder and Coder on a regular basis.

My experiments I are almost always in Builder, with added Code Components. I don't ever break out and switch to pure code. I use code for other things (e.g. making my 'conditions' .csv files, making stimuli)


Going further
~~~~~~~~~~~~~~~~~~~~~~

Builder interface:
    - `Building Experiments in PsychoPy <https://uk.sagepub.com/en-gb/eur/building-experiments-in-psychopy/book253480>`_ by Peirce and MacAskill (2018, Sage Publications)

Python programming (for experimental psych):
    - `Programming Visual Illusions for Everyone <http://www.springer.com/gb/book/9783319640655>`_ by Marco Bertamimi (2017, Springer) 
    - `Python for Experimental Psychologists <https://www.amazon.co.uk/Python-Experimental-Psychologists-Edwin-Dalmaijer/dp/1138671576>`_ by Edwin Dalmaijer (2017, Routledge)

So, let's go on and learn some :ref:`session13Days`...
