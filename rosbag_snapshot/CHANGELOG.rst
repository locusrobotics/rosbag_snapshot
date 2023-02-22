^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rosbag_snapshot
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.0 (2023-02-22)
------------------
* RST-5409 Retain latched messages from each unique publisher (#2)
* Contributors: nleblanc-lr

1.0.4 (2022-04-11)
------------------
* Update _is_latched comment to specify that lock is not obtained
* Don't alter the start_time of the trigger request
* Ensure latched topics have timestamps >= start of snapshot bag
* Retain latest latched messages
* Add count limit option (`#18 <https://github.com/locusrobotics/rosbag_snapshot/issues/18>`_)
  Add the option to specify a maximum number of messages per topic.
* Fix `#13 <https://github.com/locusrobotics/rosbag_snapshot/issues/13>`_ (`#15 <https://github.com/locusrobotics/rosbag_snapshot/issues/15>`_)
* change NO_DATA to NO_DATA_MESSAGE to avoid conflict with boost (`#12 <https://github.com/locusrobotics/rosbag_snapshot/issues/12>`_)
* Contributors: David V. Lu!!, Jørgen Borgesen, Noah LeBlanc, zmp-virgru
