Kinyu Demo
==========

+-----------------+----------------+---------------+------------+
| :ref:`genindex` |:ref:`modindex` | :ref:`search` | `GitHub`_. |
+-----------------+----------------+---------------+------------+

.. _GitHub: https://github.com/tayglobal/kinyu-demo

Introduction
------------

This is a repository that contains interesting demos that can be applied in the financial industry. 

There are also some modules that assist the demo.

Below are some demos:

`Dependency Graph <examples/Dependency_Graph.html>`_

Demonstrate the dependency graph heavily used in Goldman Sache (SecDB), JPMorgan (Athena), Bank of America (Quartz) and Beacon.io.

`IR Risk in Multicurve Env <examples/IR_Risk_in_Multicurve_Env.html>`_

For a single swap and a portfolio, show how we could display a risk ladder. The tenors would be based on market data used to build the curves. Two curves are involved in this demo, a projection curve and a funding curve.

`Remote Import <examples/Remote_Import.html>`_

Python is an extremely dynamic and flexible language. In this demo, the goal is to show how we can use python’s path_hooks mechanism to change imports from using local filesystem to a remote source.

As a bonus, this article also demonstrates creating necessary AWS resources via Cloudformation and how to remove them with a single command. There will be some basic performance analysis of the each remote source.


Kinyu Modules
-------------

Below are the modules used for the demos.


.. toctree::
   main
   rimport
   developer

