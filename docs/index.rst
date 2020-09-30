python-archinstall Documentation
================================

| **python-archinstall** *(or, archinstall for short)* is a helper library to install Arch Linux and manage services, packages and other things.
| It comes packaged with different installers *(shopped as scripts)*, such as _guided and _automated installer that can be run as _Python modules.
| 
| Here's a `demo <https://www.youtube.com/watch?v=9Xt7X_Iqg6E>`_ using the guided installer.


Some of the features of Archinstall are:

* **No external dependencies or installation requirements.** Runs without any external requirements or installation processes.

* **Single threaded and context friendly.** The library always executed calls in sequential order to ensure installation-steps don't overlap or executes in the wrong order. It also supports *(and uses)* context wrappers to ensure things such as `sync` are called so data and configurations aren't lost.

* **Supports standalone executable** The library can be compiled into a single executable and run on any system with or without Python. This is ideal for live mediums that don't want to ship Python as a big dependency.

.. toctree::
   :maxdepth: 3
   :caption: Installing

   installing/python
   installing/binary

.. toctree::
   :maxdepth: 3
   :caption: Usage & Examples

   examples/python
   examples/binary
   examples/scripting

.. toctree::
   :maxdepth: 3
   :caption: Programming Guide

   programming_guide/requirements
   programming_guide/basic_concept

.. toctree::
   :maxdepth: 3
   :caption: Getting help

   help/discord
   help/issues

.. toctree::
   :maxdepth: 3
   :caption: API Reference

   archinstall/Installer