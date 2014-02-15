assettocorsa-traction-circle
============================

Plots the acceleration values (G) of the car so the driver can see how well the interaction with traction during cornering and breaking.

Keeps the last X seconds worth of observed values and automatically fades them by age (brighter values are more recent) leaving a trail.

Screenshot
==========

![In game screenshot](assetto-corsa-traction-circle.png "In game screenshot")

Installation
============

Copy the apps/python/traction-circle directory to your:

   assettocorsa\apps\python

directory.  This is often in C:\Program Files (x86)\Steam\steamapps\common\assettocorsa\apps\python.

Roadmap
=======

In the future I would like to:

* Highlight when the slip angle/wheel spin or lockup is happening to flag when the driver has used up too much traction
* Plot a moving average as a line-plot to show course-grained view than the scatter-plot