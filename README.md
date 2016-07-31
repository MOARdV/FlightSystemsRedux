# FlightSystemsRedux
RasterPropMonitor-enabled IVA configurations for the Kerbal Space Program

## Overview

FlightSystemsRedux is a mod that contains updated RasterPropMonitor IVA configurations for use in KSP.
It is a revision and update of the FASA Gemini Modernization 2.0 from 2014, and it provides a
way to showcase RasterPropMonitor capabilities without resorting to all-glass cockpits.

## Requirements

The following are all requirements for using FlightSystemsRedux (and not included in this package):

* Kerbal Space Program v1.1.3 or later
* [ASET Avionics Pack](http://forum.kerbalspaceprogram.com/threads/129364) v1.0 or later
* [ASET Props Pack](http://forum.kerbalspaceprogram.com/threads/129305) v1.3 or later
* [Module Manager](http://forum.kerbalspaceprogram.com/threads/55219) v2.6.25 or later
* [RasterPropMonitor](http://forum.kerbalspaceprogram.com/threads/117471) v0.27.0 or later

In addition, one or both of these mods is needed to use the existing IVAs.
* [FASA](http://forum.kerbalspaceprogram.com/threads/24867) v5.40 or later for the FASA Gemini pod
* [Yarbrough Mk. 1-1 A2](http://forum.kerbalspaceprogram.com/index.php?/topic/88604-wip-105-2-kerbal-command-pod-mk-1-1-a2-alpha-04-spacedock/) Alpha 0.4 or later for the Yarbrough Mk. 1-1 A2 pod

Earlier versions of the listed mods may work, but such configurations are untested and unsupported.

These IVAs have additional functionality when the following mods are installed:

* [Kerbal Alarm Clock](http://forum.kerbalspaceprogram.com/index.php?/topic/22809-10x-kerbal-alarm-clock-v3500-dec-3/) - adds the ability to view the time until the next Kerbal Alarm Clock alarm triggers when using the auxiliary digital timer.
* [MechJeb](http://forum.kerbalspaceprogram.com/index.php?/topic/111978-105-anatid-robotics-mumech-mechjeb-autopilot-256-23-feb-2016/) - adds launch, landing, maneuver node, and rendezvous autopilots, Smart A.S.S. functionality, as well as the ability to configure launch parameters, orbit changes, and rendezvous maneuvers.
* [RealChute](http://forum.kerbalspaceprogram.com/index.php?/topic/52931-10511wenkel-corporation-realchute-parachute-systems-v14x3-020416-11-prerelease-available/) - adds the ability to arm RealChute parachutes for deployment, in addition to deploying parachutes.

As of version 4.1.0 of this mod, the FASA Gemini pod has been moved to legacy status.  There have been no updates to the IVA to take
advantage of the latest ASET props and RasterPropMonitor, and all relevant components have been moved to the Legacy folder.
The IVA may not work correctly (an update will take place later; pull requests with fixes are welcome if someone doesn't want
to wait).

## Installation

Merge the GameData folder in this archive with the GameData folder in your KSP installation.  The contents of this archive do not overwrite existing files anywhere but GameData/MOARdV/FlightSystemsRedux.

Removing this mod is as simple as deleting the GameData/MOARdV/FlightSystemsRedux folder.

If you are not using the FASA Gemini pod, you may safely delete the GameData/MOARdV/FlightSystemsRedux/Legacy folder.

## Usage

TL;DR: start playing.  Almost everything is clickable, or it provides information.  The IVA is retrofitted to existing flights, even, so there's no danger to existing save games.

Long version: Visit the [Wiki](https://github.com/MOARdV/FlightSystemsRedux/wiki) for this mod for detailed descriptions.

## Manifest

What's included in this package?

* Module Manager configs to replace the props in the FASA Gemini capsule and the Yarbrough Mk. 1-1 A2 capsule, updating those pods with new interiors.
* Module Manager configs to modify the FASA Gemini nose cones with docking port cameras and a radar module to allow target acquisition.
* Module Manager configs to add cameras to the FASA Probe Camera, converting it into a RasterPropMonitor-enabled camera.
* Many MOARdV customized configurations of existing ASET Props and ASET Avionics parts.

Other directories contain configurations for MFDs, replacement textures used for customized props, et cetera.

## Licenses

The contents of this mod are released under the Creative Commons [Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license (CC BY-NC-SA 4.0) with the following exceptions:

All props and textures included in this mod were originally created by Alexustas.  They are covered by the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License (CC BY-NC-SA).
Some of them have been modified for inclusion in this mod.

## Revision History

### 4.1.0 - 2016
* Update of Yarbrough Mk. 1-1 A2 using latest props and RasterPropMonitor features.
* Move Gemini to Legacy status - I don't have the spare time to maintain and update it at the moment.
* Props alexustas created that are part of upcoming ASET props packs have been removed from this distribution.
If you do not have the latest pack, or it has not been released, you will have missing props in the IVA.

### 4.0.0 - 19 APR 2016
* Release version of Yarbrough Mk. 1-1 A2.

### 4.0.0a1 - 7 APR 2016

* Addition of the Yarbrough Mk. 1-1 A2 IVA.
* Many additional props from alexustas.

### 3.0.0b - 11 NOV 2015

* Final update to Gemini pod.

### 3.0.0a2 - 24 OCT 2015

* Addition of the x-pointer instrument to the package.
* Addition of controls on the pilot's panel to set MechJeb launch and orbit management controls.

### 3.0.0a1 - 11 OCT 2015

* New FASA Gemini release using ASET Props, ASET Avionics, plus some new props.

### 2.0 - 29 JUN 2014 

* No longer available
* New FASA Gemini release incorporating some FASA Apollo props.

### 1.1 - 29 JUN 2014

* No longer available
* Bugfix release to account for updated RasterPropMonitor.

### 1.0 - 21 JAN 2014

* No longer available
* Initial release covering the FASA Gemini pod.
