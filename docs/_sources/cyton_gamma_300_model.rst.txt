Cyton gamma 300 Model
=====================

.. contents:: Table of Contents
    :depth: 5
    :backlinks: top

In this document we describe a step-by-step guide to get started with the ``cyton_gamma_300`` robotic arm.
For this guide we assume that a user is on the Ubuntu distribution (since we need ROS, and ROS provides
installers for Ubuntu), and has access to the available command-line utilities.
Administrative access is a plus and might be required when access to the serial is restricted on the system.

In order to get started one needs:

* a ``cyton_gamma_300``  arm;

* a Linux PC with ROS installed;

* `DynamixelWizard`_ software from for updating firmware of the motors;

.. _DynamixelWizard: https://www.robotis.us/dynamixel-management/

---------------------------------
0. Getting started plan
---------------------------------

In order to get started we are going to follow the steps below:

1. Install the required dependencies;

2. Run the available code in simulation

3. Run the code on the actual robot
