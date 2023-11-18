# Github repository TOC
This readme lists our repositories and the links for better access.

# ROS Marine Vehicle Packages (ROS-MVP)
- [mvp_mission](https://github.com/uri-ocean-robotics/mvp_mission):  MVP Helm and beahvior plugins.

- [mvp_control](https://github.com/uri-ocean-robotics/mvp_control): low-level vehicle control using thruster allocation and QP solver.

- [mvp_msgs](https://github.com/uri-ocean-robotics/mvp_msgs): MVP messages and services. 

- [stonefish_mvp](https://github.com/uri-ocean-robotics/stonefish_mvp): a modified ros wrapper for the great [Stonefish simulator](https://github.com/patrykcieslak/stonefish).

- Reference
    - [Ocean's paper](https://ieeexplore.ieee.org/abstract/document/9977346): information about the original MVP design. Software has been consistently updated since then.
    - [Thesis](https://www.proquest.com/docview/2766097939?pq-origsite=gscholar&fromopenview=true). A detailed information about the design of the MVP framework from the original creator Emir.


# Under-ice nav
- [MSCKF-DVIO](https://github.com/GSO-soslab/msckf_dvio): MSCKF VIO with DVL. [paper](https://arxiv.org/abs/2303.17005) (IROS2023). 

- [under-ice rov](https://github.com/GSO-soslab/rov): configuration files for the under-ice rov. [paper](https://ieeexplore.ieee.org/abstract/document/9977140).
- [Under-ice Dataset](): comming soon.

# Vehicle configurations
- [alpha_rise_auv](https://github.com/GSO-soslab/alpha_rise_auv): our sensor-loaded AUV for iceberg mapping missions.

- [alpha_std_auv](https://github.com/uri-ocean-robotics/alpha_std_auv). An example repository for trying out mvp in stonefish simulation environment.

- [alpha_core](https://github.com/uri-ocean-robotics/alpha_core): core hardware interfaces sensor drivers (external)

- [alpha_img_auv](https://github.com/GSO-soslab/alpha_img_auv): configuration of an alpha iteration with forward-looking sonar and scanning sonar for subsea mapping and sonar image processing research.

- [race_auv](https://github.com/GSO-soslab/race_auv): configuration of a box-type AUV used for underwater resident projects.


# Sensor drivers
- [BlueRobotics Ping360](https://github.com/GSO-soslab/bluerobotics_ping360/tree/aa4834644963b24a9c4dc10f6e6268c0e43f88b7): ROS-noetic driver for Ping 360 with modifications to produce point cloud data.

- [BlueRobotics Bar30](https://github.com/GSO-soslab/bluerobotics_pressure/tree/237903a1485b3bd5c51d471c291b6e90f11d7654): Blue Robotics Bar30 pressure tempreature sensor ROS driver.

- [Power monitoring](https://github.com/GSO-soslab/power_monitor/tree/86118e67194bd37db8fe7205e9260bc41fd4eec7): ROS driver to interface with MCP3422 ADC chip to read system voltage and current.

- [Waterlinked DVL](https://github.com/uri-ocean-robotics/waterlinked_dvl/tree/31216e175184bc7f410d29df7858110b1db75d26): Water Linked DVL ROS driver (ethernet).

- [XSens MTi600](https://github.com/GSO-soslab/xsens_mti_ros_driver/tree/7aa46b7f0a0576609062aaf46c518940e5fb4853): XSens MTi ROS driver, tested on 600-series and 1-series.

- [Nortek DVL-1000](https://github.com/GSO-soslab/nortek_dvl_ethernet): ROS driver for Nortek DVL-1000 (Ethernet version).

- [Nortek DVL-1000](https://github.com/GSO-soslab/nortek_dvl): ROS driver for Nortek DVL-1000 (serial version).


# Others
- [jackal setup](https://github.com/GSO-soslab/jackal_ocg120g): Jackal setup for OCG120G class.
