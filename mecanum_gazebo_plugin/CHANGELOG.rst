^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mecanum_gazebo_plugin
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2020-07-08)
------------------
* Changed to use a passive rolling ball as a model instead of modifying the friction
* Removed the following parameters: 
  fixedLinkName, rollerAngle, rollerFriction, rollerSkidFriction
* Added axis parameter
* Removed dependency on ODE
* Added readme

0.1.0 (2019-07-22)
------------------

0.0.3 (2018-04-26)
------------------

0.0.2 (2017-05-08)
------------------
* Disabled tests for mecanum_gazebo_plugin.
* Contributors: Tony Baltovski

0.0.1 (2016-05-25)
------------------
* Rewound version numbers and removed changes logs.
* Disable building plugin (only works on Gazebo 5).
* Remove experimental std::abs call from geometry.
* Parameterize roller friction, add gazebo_ros_control PID gains.
* Add some specific TODO callouts.
* Remove assignment from within if-condition.
* Remove unused header.
* Fix linter warnings.
* Add roslint.
* Use M_PI, remove extra line.
* Fix url in package.xml
* Fix indentation, add license.
* Remove unnecessary build stuff.
* Add roller angle parameter.
* Skeleton of a mecanum gazebo plugin.
* Contributors: Mike Purvis, Tony Baltovski
