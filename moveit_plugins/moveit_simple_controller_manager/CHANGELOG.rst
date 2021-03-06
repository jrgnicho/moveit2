^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package moveit_simple_controller_manager
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.0 (2020-02-17)
------------------
* [improve] MoveItSimpleControllerManager refactor parameter lookup
* [fix] Fix plugin install of MoveItSimpleControllerManager
* [port] Port moveit_simple_controller_manager to ROS 2 (`#158 <https://github.com/ros-planning/moveit2/issues/158>`_)
* Contributors: Henning Kayser, Jafar Abdi

1.0.1 (2019-03-08)
------------------
* [improve] Apply clang tidy fix to entire code base (Part 1) (`#1366 <https://github.com/ros-planning/moveit/issues/1366>`_)
* Contributors: Yu, Yan

1.0.0 (2019-02-24)
------------------
* [maintenance] cleanup SimpleControllerManager https://github.com/ros-planning/moveit/pull/1352
* Contributors: Robert Haschke

0.10.8 (2018-12-24)
-------------------

0.10.7 (2018-12-13)
-------------------

0.10.6 (2018-12-09)
-------------------
* [maintenance] Code Cleanup (`#1196 <https://github.com/ros-planning/moveit/issues/1196>`_)
* Contributors: Robert Haschke

0.10.5 (2018-11-01)
-------------------

0.10.4 (2018-10-29)
-------------------

0.10.3 (2018-10-29)
-------------------

0.10.2 (2018-10-24)
-------------------
* [maintenance] various compiler warnings (`#1038 <https://github.com/ros-planning/moveit/issues/1038>`_)
* [maintenance] add minimum required pluginlib version (`#927 <https://github.com/ros-planning/moveit/issues/927>`_)
* Contributors: Mikael Arguedas, Mohmmad Ayman, Robert Haschke, mike lautman

0.10.1 (2018-05-25)
-------------------
* switch to ROS_LOGGER from CONSOLE_BRIDGE (`#874 <https://github.com/ros-planning/moveit/issues/874>`_)
* Contributors: Mikael Arguedas, Xiaojian Ma

0.9.11 (2017-12-25)
-------------------

0.9.10 (2017-12-09)
-------------------
* [capability][kinetic onward] optionally wait for controllers indefinitely (`#695 <https://github.com/ros-planning/moveit/issues/695>`_)
* Contributors: Bruno Brito, Michael Görner

0.9.9 (2017-08-06)
------------------

0.9.8 (2017-06-21)
------------------
* [fix] include order (`#529 <https://github.com/ros-planning/moveit/issues/529>`_)
* Contributors: Michael Goerner

0.9.7 (2017-06-05)
------------------

0.9.6 (2017-04-12)
------------------

0.9.5 (2017-03-08)
------------------
* [fix][moveit_ros_warehouse] gcc6 build error `#423 <https://github.com/ros-planning/moveit/pull/423>`_ 
* [enhancement] Remove "catch (...)" instances, catch std::exception instead of std::runtime_error (`#445 <https://github.com/ros-planning/moveit/issues/445>`_)
* Contributors: Bence Magyar, Dave Coleman

0.9.4 (2017-02-06)
------------------
* [fix] assertion error when result not returned (`#378 <https://github.com/ros-planning/moveit/issues/378>`_)
* [maintenance] clang-format upgraded to 3.8 (`#367 <https://github.com/ros-planning/moveit/issues/367>`_)
* Contributors: Dave Coleman, Michael Ferguson

0.9.3 (2016-11-16)
------------------

0.5.7 (2016-01-30)
------------------
* expose headers of moveit_simple_controller_manager
* Removed redundant logging information
* More informative warning message about multi-dof trajectories.
* Contributors: Dave Coleman, Dave Hershberger, Mathias Lüdtke

0.5.6 (2014-03-23)
------------------
* Allow simple controller manager to ignore virtual joints without failing
* Contributors: Dave Coleman

0.5.5 (2013-09-30)
------------------
* properly fill in the gripper command effort
* allow trajectories with >1 points, use the last point of any trajectory
* added better error reporting for FollowJointTrajectoryControllers

0.5.4 (2013-09-24)
------------------

0.5.3 (2013-09-23)
------------------
* make things a bit more robust
* make headers and author definitions aligned the same way; white space fixes
* fix `#1 <https://github.com/ros-planning/moveit_plugins/issues/1>`_

0.5.1 (2013-07-30)
------------------
* ns parameter is now action_ns, get rid of defaults

0.5.0 (2013-07-16)
------------------
* white space fixes (tabs are now spaces)

0.4.1 (2013-07-03)
------------------
* minor updates to package.xml

0.4.0 (2013-06-06)
------------------
* debs look good, bump to 0.4.0

0.1.0 (2013-06-05)
------------------
* add metapackage, clean up build in controller manager
* remove the now dead loaded controller stuff
* break out follow/gripper into separate headers
* initial working version
