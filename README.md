
# OpenVMS Compatibility Library

A collection of DBL subroutines and functions that implement, emulate or
shim the functionality of various OpenVMS system service routines.

Routines that contain actual implementation code are intended be useful
when migrating a DBL application from OpenVMS to another platform.

Shim routines (those that don't contain actual implementation code) are
intended to make it possible to edit and debug OpenVMS code within a Visual
Studio (and to a lesser extend Workbench) development environment while
enjoying features such as IntelliSense.

Included in this environment are both a Workbench workspace file and a
Visual Studio solution. Open one of these in your preferred IDE and use
the build command to compile and link the ELB which is named VMSLib.elb.

