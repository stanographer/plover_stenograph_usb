Plover Stenograph USB
=====================

Purpose
-------
Implementation of Stenograph USB protocol for Diamanté and Luminex machines. Based on work by Ted Morin and Keith McCready.

Files
-----
* system.py - Contains key mappings and orthographic rules.
* stenograph.py - Thread-based monitoring of the Stenograph machine output.
* README.rst - Readme.
* setup.cfg - Python setup info.

Installation
------------
1. Make sure you have the Plover Plugin Manager (https://github.com/benoit-pierre/plover_plugins_manager) installed.
2. Pull down repo.
3. Run command `python3 -m pip install -e .` .
4. Make sure your Stenograph machine is plugged in and write a stroke to start a job.
5. Run Plover and select "Stenograph USB" from the dropdown list.