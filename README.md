# FlightSystemsRedux
RasterPropMonitor-enabled IVA configurations for the Kerbal Space Program

## Overview

FlightSystemsRedux is a mod that contains updated RasterPropMonitor IVA configurations for use in KSP.
It is a revision and update of the FASA Gemini Modernization 2.0 from 2014, and it provides a
way to showcase RasterPropMonitor capabilities without resorting to all-glass cockpits.

Also included are many ASET props created by alexustas that have not been released into the ASET Props Pack
or ASET Avionics Pack.

## Requirements

The following are all requirements for using FlightSystemsRedux (and not included in this package):

* Kerbal Space Program v1.1.0 or later
* [ASET Avionics Pack](http://forum.kerbalspaceprogram.com/threads/129364) v1.0 or later
* [ASET Props Pack](http://forum.kerbalspaceprogram.com/threads/129305) v1.3 or later
* [Module Manager](http://forum.kerbalspaceprogram.com/threads/55219) v2.6.21 or later
* [RasterPropMonitor](http://forum.kerbalspaceprogram.com/threads/117471) v0.25.0 or later

In addition, one or both of these mods is needed to use the existing IVAs.
* [FASA](http://forum.kerbalspaceprogram.com/threads/24867) v5.40 or later for the FASA Gemini pod
* [Yarbrough Mk. 1-1 A2](http://forum.kerbalspaceprogram.com/index.php?/topic/88604-wip-105-2-kerbal-command-pod-mk-1-1-a2-alpha-04-spacedock/) Alpha 0.4 or later for the Yarbrough Mk. 1-1 A2 pod

Earlier versions of the listed mods may work, but such configurations are untested and unsupported.

## Installation

Merge the GameData folder in this archive with the GameData folder in your KSP installation.  The contents of this archive do not overwrite existing files anywhere but GameData/MOARdV/FlightSystemsRedux.

If you have a legacy version of the Gemini replacement IVA (version 2.0 or earlier), you should delete it.  It is not fully compatible with current versions of RasterPropMonitor.

Removing this mod is as simple as deleting the GameData/MOARdV/FlightSystemsRedux folder.

## Usage

TL;DR: start playing.  Almost everything is clickable, or it provides information.  The IVA is retrofitted to existing flights, even, so there's no danger to existing save games.

Long version: Visit the [Wiki](https://github.com/MOARdV/FlightSystemsRedux/wiki) for this mod for detailed descriptions.

## Manifest

What's included in this package?

* Module Manager configs to replace the props in the FASA Gemini capsule and the Yarbrough Mk. 1-1 A2 capsule, updating those pods with new interiors.
* Module Manager configs to modify the FASA Gemini nose cones with docking port cameras and a radar module to allow target acquisition.
* Module Manager configs to add cameras to the FASA Probe Camera, converting it into a RasterPropMonitor-enabled camera.
* Many, many MOARdV customized configurations of existing ASET Props and ASET Avionics parts.

In addition, there are many props from alexustas that have not been released in his existing parts packs.  Each part is in its own directory.

* ARRT - an altitude / range-range rate indicator useful for landing and docking.
* ASET_ClockTimer - an analog clock that automatically configures itself for Earth (24 hour) or Kerbin (6 hour) days that includes a stopwatch feature.
* ASET_DSKY - inspired by the Apollo DSKY, the ASET DSKY provides orbital and rendezvous information.
* ASET_SignalLamp - a configurable incandescent indicator lamp.
* ASET_VPG - a single-scale analog bar-graph style indicator (good as a fuel gauge, pressure gauge, etc).
* ASET_VPGDual - a dual-scale gauge (good for tracking stage and total quantities, for instance, or static and dynamic pressure).
* FDAI - The Flight Directory / Attitude Indicator, based on the Apollo FDAI.  A replacement advanced navball.
* FDAI_GMCP - The control panel for the FDAI.
* FlagIndicator - Based on the indicators in Apollo - a rectangular bracket holding an illuminated flag (indicator lamp), with a configurable caption.
* Monitor_4char - A simple monitor intended for a 1 row, 4 character display.
* Monitor_8char - A simple monitor intended for a 1 row, 8 character display.
* MultiSwitcher_3pos - A rotary switch with three positions.
* MultiSwitcher_4pos - A rotary switch with four positions.
* NumInputDial - A knob that can be rotated for numeric inputs, with a "Select" button on its tip.
* NumInputDial_NoButton - Same as above, but with a configurable graphic on its tip instead of a button.
* RetroButton - An Apollo-like illuminated push button / switch.
* RetroWarningLight - An Apollo-like illuminated warning plaque.
* RotationCtrl_V2 - A joystick without an additional hardware (for surface placement).
* SquareMonitorTypeA and SquareMonitorTypeB - A 1:1 aspect ratio monitor with no buttons.  One version includes mounting screws, the other does not.
* Switch_Tumbler_3Pos - A mechanical tumbler switch with three positions.
* TWR_Indicator - An analog bar gauge for tracking thrust to weight ratio.
* Xpointer - An analog display used for zeroing lateral speeds during landing, and for aligning with and matching velocity with an orbital target.

## Licenses

The contents of this mod are released under the Creative Commons [Attribution-NonCommercial-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-nc-sa/4.0/) license (CC BY-NC-SA 4.0) with the following exceptions:

All props and textures included in this mod were originally created by Alexustas.  They are covered by the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License (CC BY-NC-SA).
Some of them have been modified for inclusion in this mod.

## Revision History

4.0 - APR 2016 - Addition of the Yarbrough Mk. 1-1 A2 IVA + many unreleased props from alexustas.

3.0 - NOV 2015 - New FASA Gemini release using ASET props.

2.0 - 29 JUN 2014 - New FASA Gemini release incorporating some FASA Apollo props.

1.1 - 29 JUN 2014 - Bugfix release to account for updated RasterPropMonitor behavior.

1.0 - 21 JAN 2014 - Initial release covering the FASA Gemini pod.
