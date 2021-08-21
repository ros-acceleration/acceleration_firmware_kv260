^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package acceleration_firmware_kv260
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.5.0 (2021-06-03)
-------------------
* Add Apache 2.0 LICENSE
* Review README, add supported boards
* Image fixes

0.4.0 (2021-05-11)
-------------------
* Renamed to acceleration_firmware_xilinx
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
