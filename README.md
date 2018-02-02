# Ansible Role: ROS Installation

[![Build Status](https://travis-ci.org/ohing504/ansible-role-ros-installation.svg?branch=master)](https://travis-ci.org/ohing504/ansible-role-ros-installation)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://raw.githubusercontent.com/crazyguitar/pysheeet/master/LICENSE)

An Ansible role that installs ROS kinetic on Ubuntu

## Requirements

None

## Role Variables

Available variables are listed below, along with default values:

    ros_installation_ros_release: "kinetic"
    ros_installation_ros_package: "desktop-full"
    ros_installation_ros_repository: "http://packages.ros.org/ros/ubuntu"
    ros_installation_ros_keyserver: "hkp://ha.pool.sks-keyservers.net:80"
    ros_installation_ros_keyid: "421C365BD9FF1F717815A3895523BAEEB01FA116"

    ros_installation_install_dependencies: true

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - { role: ohing504.ros-installation }

## License

MIT

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
