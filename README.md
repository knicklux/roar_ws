ROAR

Robot OS Awesome Rocketry

ROAR exports KSP's API via Ros2. It is built on top of kRPC and requires the kRPC mod to be running.

This repo contains all files and instructions needed to build ROAR.

Current kRPC dependency: kRPC 0.4.5

Please read https://krpc.github.io/krpc/cpp/client.html#using-the-library

This is WIP. Please enjoy nonetheless and feel free to file issues.

Intended use:

Use the space center node to manage vessels and select the active vessel.

Use the active vessel node to control the active vessel.

Create dedicated nodes for individual vessels if required.

Add or remove kRPC maneuver nodes from the vessels to manage maneuver nodes (using krpc wrapper messages?)

Query celestial bodies directly via krpc

The purpose of ROAR is not to hide kRPC away, but to provide a Ros2 API to your rocket as if it was physical.
