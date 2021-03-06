.. _sdk_qtquick_particles_gravity:

QtQuick.Particles Gravity
=========================

For applying acceleration in an angle

+--------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| Import Statement:                                                                                                                                      | import QtQuick.Particles 2.0                                                                                                                           |
+--------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| Inherits:                                                                                                                                              | `Affector </sdk/apps/qml/QtQuick/Particles.Affector/>`_                                                                                                |
+--------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+

Properties
----------

-  `acceleration </sdk/apps/qml/QtQuick/Particles.Gravity/#acceleration-prop>`_  : real
-  `angle </sdk/apps/qml/QtQuick/Particles.Gravity/#angle-prop>`_  : real
-  `magnitude </sdk/apps/qml/QtQuick/Particles.Gravity/#magnitude-prop>`_  : real

Detailed Description
--------------------

This element will accelerate all affected particles to a vector of the specified magnitude in the specified angle. If the angle and acceleration do not vary, it is more efficient to set the specified acceleration on the Emitter.

This element models the gravity of a massive object whose center of gravity is far away (and thus the gravitational pull is effectively constant across the scene). To model the gravity of an object near or inside the scene, use PointAttractor.

Property Documentation
----------------------

.. _sdk_qtquick_particles_gravity_acceleration:

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| acceleration : real                                                                                                                                                                                                                                                                                          |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Name changed to magnitude, will be removed soon.

.. _sdk_qtquick_particles_gravity_angle:

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| angle : real                                                                                                                                                                                                                                                                                                 |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Angle of acceleration.

.. _sdk_qtquick_particles_gravity_magnitude:

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| magnitude : real                                                                                                                                                                                                                                                                                             |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Pixels per second that objects will be accelerated by.

