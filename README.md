ecl_lite
========

The ecl-lite stack includes packages with few dependencies on either system
or c++ functionality. This makes it ideal for very embedded builds where
many of the usual mechanisms are unavailable.

* No malloc/new
* No exceptions
* Minimal templates
       
It also includes a few packages which standardise lower level
api (e.g. posix/win32) with drop-ins to make them properly cross-platform,

The development branch now uses ament. The most recent catkin based branches are on [release/0.61-indigo-kinetic](https://github.com/stonier/ecl_lite/tree/release/0.61-indigo-kinetic) and [release/0.61-melodic](https://github.com/stonier/ecl_lite/tree/release/0.61-melodic).

