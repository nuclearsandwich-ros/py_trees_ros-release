# Py Trees for ROS

Behaviours, trees and utilities that extend py_trees for use
with ROS.

## :construction: Under Construction

The `devel` branch is in the process of being rebuilt for ROS2.

## PyTrees-ROS Ecosystem


| ROS2 | [Crystal][crystal-build-farm] |  ROS1 | [Melodic][melodic-build-farm] | [Kinetic][kinetic-build-farm] |
|:---:|:---:|:---:|:---:|:---:|
| [py_trees][py-trees-ros-index] | [![1.2.x][1.2.x-sources-image]][py-trees-sources-1.2.x]<br/>[![Build Status][py-trees-build-status-crystal-image]][py-trees-build-status-crystal]<br/>[![1.2.x-Docs][1.2.x-rtd-image]][py-trees-docs-1.2.x] | [py_trees][py-trees-wiki] | [![0.6.x][0.6.x-sources-image]][py-trees-sources-0.6.x]<br/>[![Build Status][py-trees-build-status-melodic-image]][py-trees-build-status-melodic]<br/>[![Docs Status][py-trees-docs-melodic-image]][py-trees-docs-melodic] | [![0.5.x][0.5.x-sources-image]][py-trees-sources-0.5.x]<br/>[![Build Status][py-trees-build-status-kinetic-image]][py-trees-build-status-kinetic]<br/>[![Docs Status][py-trees-docs-kinetic-image]][py-trees-docs-kinetic] |
| [py_trees_ros_interfaces][py-trees-ros-interfaces-ros-index] | [![1.1.x][1.1.x-sources-image]][py-trees-ros-interfaces-sources-1.1.x]<br/>[![Build Status][py-trees-ros-interfaces-build-status-crystal-image]][py-trees-ros-interfaces-build-status-crystal]<br/>![1.1.x-Docs][not-available-docs-image] | [py_trees_msgs][py-trees-msgs-wiki] | [![0.3.x][0.3.x-sources-image]][py-trees-msgs-sources-melodic]<br/>[![Build Status][py-trees-msgs-build-status-melodic-image]][py-trees-msgs-build-status-melodic]<br/>[![Docs Status][py-trees-msgs-docs-melodic-image]][py-trees-msgs-docs-melodic] | [![0.3.x][0.3.x-sources-image]][py-trees-msgs-sources-kinetic]<br/>[![Build Status][py-trees-msgs-build-status-kinetic-image]][py-trees-msgs-build-status-kinetic]<br/>[![Docs Status][py-trees-msgs-docs-kinetic-image]][py-trees-msgs-docs-kinetic] |
| [py_trees_ros][py-trees-ros-ros-index] | [![1.0.x][1.0.x-sources-image]][py-trees-ros-sources-1.0.x]<br/>[![1.2.x-Docs][1.0.x-rtd-image]][py-trees-ros-docs-1.0.x] | [py_trees_ros][py-trees-ros-wiki] | [![0.5.x][0.5.x-sources-image]][py-trees-ros-sources-0.5.x]<br/>[![Build Status][py-trees-ros-build-status-melodic-image]][py-trees-ros-build-status-melodic]<br/>[![Docs Status][py-trees-ros-docs-melodic-image]][py-trees-ros-docs-melodic] | [![0.5.x][0.5.x-sources-image]][py-trees-ros-sources-0.5.x]<br/>[![Build Status][py-trees-ros-build-status-kinetic-image]][py-trees-ros-build-status-kinetic]<br/>[![Docs Status][py-trees-ros-docs-kinetic-image]][py-trees-ros-docs-kinetic] |
| [py_trees_ros_tutorials][py-trees-ros-tutorials-ros-index] | [![1.0.x][1.0.x-sources-image]][py-trees-ros-tutorials-sources-pre-1.0.x] |  | - | - |
| | - | [rqt_py_trees][rqt-py-trees-wiki] | [![0.3.x][0.3.x-sources-image]][rqt-py-trees-sources-melodic]<br/>[![Build Status][rqt-py-trees-build-status-melodic-image]][rqt-py-trees-build-status-melodic] | [![0.3.x][0.3.x-sources-image]][rqt-py-trees-sources-kinetic]<br/>[![Build Status][rqt-py-trees-build-status-kinetic-image]][rqt-py-trees-build-status-kinetic] |

[devel-sources-image]: http://img.shields.io/badge/sources-devel-blue.svg?style=plastic
[1.2.x-sources-image]: http://img.shields.io/badge/sources-1.2.x-blue.svg?style=plastic
[1.1.x-sources-image]: http://img.shields.io/badge/sources-1.1.x-blue.svg?style=plastic
[1.0.x-sources-image]: http://img.shields.io/badge/sources-1.0.x-blue.svg?style=plastic
[0.6.x-sources-image]: http://img.shields.io/badge/sources-0.6.x-blue.svg?style=plastic
[0.5.x-sources-image]: http://img.shields.io/badge/sources-0.5.x-blue.svg?style=plastic
[0.3.x-sources-image]: http://img.shields.io/badge/sources-0.3.x-blue.svg?style=plastic

[devel-rtd-image]: https://readthedocs.org/projects/py-trees/badge/?version=devel&style=plastic
[1.2.x-rtd-image]: https://readthedocs.org/projects/py-trees/badge/?version=release-1.2.x&style=plastic
[1.0.x-rtd-image]: https://readthedocs.org/projects/py-trees/badge/?version=release-1.0.x&style=plastic
[0.6.x-rtd-image]: https://readthedocs.org/projects/py-trees/badge/?version=release-0.6.x&style=plastic
[0.5.x-rtd-image]: https://readthedocs.org/projects/py-trees/badge/?version=release-0.5.x&style=plastic

[devel-docs-image]: http://img.shields.io/badge/docs-devel-brightgreen.svg?style=plastic
[1.2.x-docs-image]: http://img.shields.io/badge/docs-1.2.x-brightgreen.svg?style=plastic
[0.6.x-docs-image]: http://img.shields.io/badge/docs-0.6.x-brightgreen.svg?style=plastic
[0.5.x-docs-image]: http://img.shields.io/badge/docs-0.5.x-brightgreen.svg?style=plastic
[0.3.x-docs-image]: http://img.shields.io/badge/docs-0.3.x-brightgreen.svg?style=plastic
[not-available-docs-image]: http://img.shields.io/badge/docs-n/a-yellow.svg?style=plastic

[1.2.x-debians-image]: http://img.shields.io/badge/debians-1.2.x-orange.svg?style=plastic
[0.6.x-debians-image]: http://img.shields.io/badge/debians-0.6.x-orange.svg?style=plastic
[0.5.x-debians-image]: http://img.shields.io/badge/debians-0.5.x-orange.svg?style=plastic
[0.3.x-debians-image]: http://img.shields.io/badge/debians-0.3.x-orange.svg?style=plastic

[crystal-build-farm]: http://repo.ros2.org/status_page/ros_crystal_default.html?q=py_trees
[melodic-build-farm]: http://repositories.ros.org/status_page/ros_melodic_default.html?q=py_trees
[kinetic-build-farm]: http://repositories.ros.org/status_page/ros_kinetic_default.html?q=py_trees

[py-trees-build-status-crystal]: http://build.ros2.org/job/Cbin_uB64__py_trees__ubuntu_bionic_amd64__binary/
[py-trees-build-status-crystal-image]: http://build.ros2.org/job/Cbin_uB64__py_trees__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[py-trees-build-status-kinetic]: http://build.ros.org/job/Kbin_uX64__py_trees__ubuntu_xenial_amd64__binary
[py-trees-build-status-kinetic-image]: http://build.ros.org/job/Kbin_uX64__py_trees__ubuntu_xenial_amd64__binary/badge/icon?style=plastic
[py-trees-build-status-melodic]: http://build.ros.org/job/Mbin_uB64__py_trees__ubuntu_bionic_amd64__binary
[py-trees-build-status-melodic-image]: http://build.ros.org/job/Mbin_uB64__py_trees__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[py-trees-docs-devel]: http://py-trees.readthedocs.io/
[py-trees-docs-1.2.x]: http://py-trees.readthedocs.io/en/release-1.2.x/
[py-trees-docs-0.6.x]: http://py-trees.readthedocs.io/en/release-0.6.x/
[py-trees-docs-0.5.x]: http://docs.ros.org/kinetic/api/py_trees/html/
[py-trees-docs-kinetic]: http://docs.ros.org/kinetic/api/py_trees/html/
[py-trees-docs-kinetic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Kdoc__py_trees__ubuntu_xenial_amd64.svg?label=docs&style=plastic
[py-trees-docs-melodic]: http://docs.ros.org/melodic/api/py_trees/html/
[py-trees-docs-melodic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Mdoc__py_trees__ubuntu_bionic_amd64.svg?label=docs&style=plastic
[py-trees-ros-index]: https://index.ros.org/p/py_trees/github-splintered-reality-py_trees
[py-trees-sources-devel]: https://github.com/splintered-reality/py_trees/tree/devel
[py-trees-sources-1.2.x]: https://github.com/splintered-reality/py_trees/tree/release/1.2.x
[py-trees-sources-0.6.x]: https://github.com/splintered-reality/py_trees/tree/release/0.6.x
[py-trees-sources-0.5.x]: https://github.com/splintered-reality/py_trees/tree/release/0.5.x
[py-trees-wiki]: http://wiki.ros.org/py_trees

[py-trees-ros-interfaces-build-status-crystal]: http://build.ros2.org/job/Cbin_uB64__py_trees_ros_interfaces__ubuntu_bionic_amd64__binary/
[py-trees-ros-interfaces-build-status-crystal-image]: http://build.ros2.org/job/Cbin_uB64__py_trees_ros_interfaces__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[py-trees-ros-interfaces-ros-index]: https://index.ros.org/p/py_trees_ros_interfaces/github-splintered-reality-py_trees_ros_interfaces
[py-trees-ros-interfaces-sources-1.1.x]: https://github.com/splintered-reality/py_trees_ros_interfaces/tree/release/1.1.x

[py-trees-ros-build-status-kinetic]: http://build.ros.org/job/Kbin_uX64__py_trees_ros__ubuntu_xenial_amd64__binary
[py-trees-ros-build-status-kinetic-image]: http://build.ros.org/job/Kbin_uX64__py_trees_ros__ubuntu_xenial_amd64__binary/badge/icon?style=plastic
[py-trees-ros-build-status-melodic]: http://build.ros.org/job/Mbin_uB64__py_trees_ros__ubuntu_bionic_amd64__binary
[py-trees-ros-build-status-melodic-image]: http://build.ros.org/job/Mbin_uB64__py_trees_ros__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[py-trees-ros-docs-1.0.x]: http://py-trees-ros.readthedocs.io/en/release-1.0.x/
[py-trees-ros-docs-kinetic]: http://docs.ros.org/kinetic/api/py_trees_ros/html/
[py-trees-ros-docs-kinetic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Kdoc__py_trees_ros__ubuntu_xenial_amd64.svg?label=docs&style=plastic
[py-trees-ros-docs-melodic]: http://docs.ros.org/melodic/api/py_trees_ros/html/
[py-trees-ros-docs-melodic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Mdoc__py_trees_ros__ubuntu_bionic_amd64.svg?label=docs&style=plastic
[py-trees-ros-ros-index]: https://index.ros.org/p/py_trees_ros/github-splintered-reality-py_trees_ros
[py-trees-ros-sources-1.0.x]: https://github.com/splintered-reality/py_trees_ros/tree/release/1.0.x
[py-trees-ros-sources-0.5.x]: https://github.com/splintered-reality/py_trees_ros/tree/release/0.5.x
[py-trees-ros-wiki]: http://wiki.ros.org/py_trees_ros


[py-trees-ros-tutorials-sources-pre-1.0.x]: https://github.com/splintered-reality/py_trees_ros_tutorials/tree/release/pre-1.0.x
[py-trees-ros-tutorials-ros-index]: https://index.ros.org/p/py_trees_ros_tutorials/github-splintered-reality-py_trees_ros_tutorials

[py-trees-msgs-build-status-kinetic]: http://build.ros.org/job/Kbin_uX64__py_trees_msgs__ubuntu_xenial_amd64__binary
[py-trees-msgs-build-status-kinetic-image]: http://build.ros.org/job/Kbin_uX64__py_trees_msgs__ubuntu_xenial_amd64__binary/badge/icon?style=plastic
[py-trees-msgs-build-status-melodic]: http://build.ros.org/job/Mbin_uB64__py_trees_msgs__ubuntu_bionic_amd64__binary
[py-trees-msgs-build-status-melodic-image]: http://build.ros.org/job/Mbin_uB64__py_trees_msgs__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[py-trees-msgs-docs-kinetic]: http://docs.ros.org/kinetic/api/py_trees_msgs/html/index-msg.html
[py-trees-msgs-docs-kinetic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Kdoc__py_trees_msgs__ubuntu_xenial_amd64.svg?label=docs&style=plastic
[py-trees-msgs-docs-melodic]: http://docs.ros.org/melodic/api/py_trees_msgs/html/index-msg.html
[py-trees-msgs-docs-melodic-image]: https://img.shields.io/jenkins/s/http/build.ros.org/job/Mdoc__py_trees_msgs__ubuntu_bionic_amd64.svg?label=docs&style=plastic
[py-trees-msgs-sources-kinetic]: https://github.com/stonier/py_trees_msgs/tree/release/0.3-kinetic
[py-trees-msgs-sources-melodic]: https://github.com/stonier/py_trees_msgs/tree/release/0.3-melodic
[py-trees-msgs-wiki]: http://wiki.ros.org/py_trees_msgs

[rqt-py-trees-build-status-kinetic]: http://build.ros.org/job/Kbin_uX64__rqt_py_trees__ubuntu_xenial_amd64__binary
[rqt-py-trees-build-status-kinetic-image]: http://build.ros.org/job/Kbin_uX64__rqt_py_trees__ubuntu_xenial_amd64__binary/badge/icon?style=plastic
[rqt-py-trees-build-status-melodic]: http://build.ros.org/job/Mbin_uB64__rqt_py_trees__ubuntu_bionic_amd64__binary
[rqt-py-trees-build-status-melodic-image]: http://build.ros.org/job/Mbin_uB64__rqt_py_trees__ubuntu_bionic_amd64__binary/badge/icon?style=plastic
[rqt-py-trees-sources-kinetic]: https://github.com/splintered-reality/rqt_py_trees/tree/release/0.3-kinetic
[rqt-py-trees-sources-melodic]: https://github.com/splintered-reality/rqt_py_trees/tree/release/0.3-melodic
[rqt-py-trees-wiki]: http://wiki.ros.org/rqt_py_trees
