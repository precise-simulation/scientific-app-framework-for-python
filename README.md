Scientific Application Framework for Python
===========================================

![Python Scientific App Example Screenshot](https://raw.githubusercontent.com/precise-simulation/scientific-app-framework-for-python/master/scientific-app-framework-screenshot.jpg)

About
-----

This is prototype and redevelopment of the [FEATool
Multiphysics](https://www.featool.com) MATLAB® framework for
scientific applications, physics and CAE simulations in Python.

The main goal is to make scientific applications and simulations easy
and accessible for users, as well as fast and easy to design and build
for application developers.

Features
--------

- Fast, easy, and definition and layout of dialogs and graphical user
  interface (GUI) by using [XML
  definitions](https://github.com/precise-simulation/scientific-app-framework-for-python/tree/main/gui%20layout%20examples).
- Automatic creation and layout of dialogs for functions and
  objects. For example, the command `dlg(Block)` will read the
  signature of the Block class, automatically create a corresponding
  dialog box, and create the object with selected parameters when
  pressing _OK_.
- Fully integrated Python scripting console.
- Automatic GUI playback functionality. Play back models as automated
  tutorials.
- 1-to-1 mapping between GUI and command line interface (CLI). Each
  GUI command and action has an equivalent CLI function call which is
  shown and logged in the console.
- Different dedicated application modes such as geometry (CAD), mesh
  generation, physics, solvers, postprocessing.
- Save and load models in equivalent binary formats and Python scripts.

Availability
------------

A prototype (work in progress) binary executable of the framework,
with a CAD Geometry mode is available for Windows in the [repository
releases](https://github.com/precise-simulation/scientific-app-framework-for-python/releases/latest).

License
-------

The binary is made available for personal evaluation and trial use
only. Please get in touch with [_Precise
Simulation_](https://www.precisesimulation.com#contact) if you would
like a custom scientific application built, or is interested in
licensing the framework.


(C) Copyright 2021 by Precise Simulation Ltd. All Rights Reserved.

FEATool™ and FEATool Multiphysics™ are trademarks of Precise
Simulation Limited. MATLAB® is a registered trademark of The
MathWorks.  All other trademarks are the property of their respective
owners. Precise Simulation Limited and its products are not affiliated
with, endorsed, sponsored, or supported by these trademark owners.
