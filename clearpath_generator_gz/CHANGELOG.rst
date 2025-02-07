^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package clearpath_generator_gz
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2023-08-25)
------------------
* Linting
* Added additional supported IMUs and GPSs
* Fix imu and gps bridge topic remapping
* Remove static tf nodes, no longer necessary
* Update topic names to match other packages
* Contributors: Hilary Luo

0.1.0 (2023-08-17)
------------------
* Renamed UST10 to UST
* Contributors: Roni Kreinin

0.0.3 (2023-07-24)
------------------
* Linting
* Added prefix launch arg for A200
* Updated param generator 'use_sim_time' implementation
* Launch generator cleanup
* Contributors: Roni Kreinin

0.0.2 (2023-07-13)
------------------
* Updated imports and getters
* Contributors: Luis Camero

0.0.1 (2023-07-05)
------------------
* Changed colour to color
* Added dependencies.repos
  Updated topic names to match API
* Support for empty namespace
  Generate tf and cmd_vel bridges
* Namespacing support
* Renamed clearpath_simulator to clearpath_gz
  clearpath_simulator is now a metapackage
  Added clearpath_generator_gz
* Contributors: Roni Kreinin
