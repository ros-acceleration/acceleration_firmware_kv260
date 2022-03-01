^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package acceleration_firmware_kv260
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.0 (2022-02-16)
-------------------
* Firmware release for Vitis 2021.2 including Yocto PetaLinux support

0.8.0 (2021-12-14)
-------------------
* Add Python 3 bindings for lttng-tools, integration with tracetools
* Fix absolute paths in cmake file created by orocos_kdl in Yocto SDK

0.7.0 (2021-10-22)
-------------------
* Add LTTng support for vanilla and PREEMPT_RT kernels
* Enhance ROS 2 Foxy with LTTng instrumentation
* Added RealSense libraries and ROS 2 packages
* Update rootfs with PREEMT_RT modules, remove leftovers
* Other minor changes

0.6.0 (2021-09-01)
-------------------
* Update mixins to set by default install-kv260
* Support multi-firmware environments in the same ROS 2 workspace
* Remove Xilinx hardcoded paths
* Add dtbo and other firmeware artifacts of supporting dfx-mgr

0.5.0 (2021-06-03)
-------------------
* Add Apache 2.0 LICENSE
* Review README, add supported boards
* Image fixes

0.4.0 (2021-05-11)
-------------------
* Renamed to acceleration_firmware_kv260
* Add new target for producing debug symbols for ZCU102
* Minor adjustments

0.3.0 (2021-03-24)
-------------------
* Re-organized artifacts for device tree and boot scripts, kernel switch now
deploys also these files
* Added imagebuilder as a git submodule from https://github.com/Xilinx/imagebuilder

0.2.0 (2021-03-16)
-------------------
* Added additional firmware artifacts for a fully preemptible kernel (PREEMPT_RT)
* Re-organized kernel Artifacts
* Documented it in ARTIFACTS.md

0.1.0 (2021-02-01)
-------------------
* Support for ZCU102.
* Artifacts are detailed within the firmware folder/.
* Altogether, about 1.4 GB.
* Includes compressed image file (~ 100 MB).
