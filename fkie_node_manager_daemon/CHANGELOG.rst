^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package fkie_node_manager_daemon
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.0 (2020-05-13)
------------------
* prepared conditions for python3  in package xml
* fkie_multimaster_fkie: got get_local_address from rosgraph.network
* fkie_multimaster: fixed python2 compatibility
* fkie_multimaster: python 3 fixes
* fkie_master_discovery: fixed usage of get local addresses
* fkie_node_manager: tests updated
* fkie_multimaster: a lot of merges for python 3 compatibility
* fkie_node_manager: fixed loop starts with associations
* fkie_node_manager: added associations parameter
* fkie_node_manager: added a screen log widget
  alternative view of current screen output with only window
* set on remote hosts the DISPLAY to :0
  this can be avoided by adding env parameter for DISPLAY with empty value
  to launch file
* search also in install/devel space for included configuration files
* fkie_node_manager_daemon: fixed show system monitor configuration after save
* fkie_node_manager_daemon: added run service to start nodes
* fkie_node_manager_daemon: updated arguments help
* Merge pull request `#113 <https://github.com/fkie/multimaster_fkie/issues/113>`_ from gstavrinos/master
  Fixed GRPC typos
* added ROS services to daemon for load (witch start nodes) launch files
* Fixed GRPC typos
* Merge branch 'master' of https://github.com/fkie/multimaster_fkie
* Make rename explicit
* fkie_node_manager_daemon: fixed resolve find in args
* fkie_node_manager: clear package path also on remote daemons
* fkie_node_manager_daemon: changed absolute path while remote start of nodes
* fkie_node_manager_daemon: remove "package://" resolve while set parameter
* Merge branch 'master' of https://github.com/fkie/multimaster_fkie
* fkie_node_manager_daemon: fixed interpret_path for script_runner
* fkie_node_manager: new feature, delete files/folders
  * fixed copy files
* fkie_node_manager: fixed copy/create new files
* fkie_node_manager_daemon: added debug output in searching for package and resource names
* fkie_node_manager_daemon: resolve pkg references while launch on remote hosts
* fkie_node_manager: improved search for included files
* fkie_node_manager: editor: fixed include files which ends with '.launch.*'
* fkie_node_manager: editor: remove block on open launch file within delayd network connection
* fkie_node_manager: fixed some problems with 'ascii' codec
* fkie_node_manager: fixed error prints to stderr
* fkie_node_manager: editor: do not test argument with defined value tag
* fkie_node_manager: editor: added test for included/setted arguments
* fix determine include parameter
* fkie_node_manager_daemon: added warnings for long delays while list sreens or open grpc connection
* fkie_node_manager_daemon: fixed save behaviour on lost connection
* fkie_node_manager: open/close grpc channels without caching
* enable cache for grpc channels again
  no cache causes os_error:"Too many open files". Perhaps it is related to
  https://github.com/grpc/grpc/issues/15759. Further tests needed.
* fkie_node_manager_daemon: do not cache channels
* fkie_node_manager_daemon: removed some format warnings
* fix test for get_packages
* test for packages
* fix for tests of formated timestamps
* Fix test for replace paths
* fkie_node_manager_daemon: added testcases for common modul
* added command prefix to advanced start configuration
  - accessible through description panel
* fkie_node_manager: fix visualization for nodes with defined machine tag
* added support for launch nodes with remote ros master uri
* fkie_node_manager: changed settings dialog
* fixed urls broken after rename packages
* fkie_node_manager_daemon: fixed diagnostics
* fkie_node_manager_daemon: changed log info on node start
* Contributors: Alexander Tiderko, George Stavrinos, Timo Röhling

1.0.0 (2019-04-30 15:12)
------------------------
* Rename packages to comply with ROS naming standard
* Contributors: Timo Röhling
