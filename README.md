ST_MyQ
======

MyQ Integration for Smart Things

This fork is an overhaul of the original done by adamheinmiller/ST_MyQ

Changes include:
  Changed tile colors to match ST garage door displays
  Enabled contact capability
  Fixed tile updated so that contact doesn't say "closed" until it's actually closed.
    Still need to fix hidden bug where door status tile will go to "unknown" instead of open/close - refresh fixes it
  Added Momentary Contact capability & implemented push() so that this now works in the ST Doors & Locks panel
    Configure as a Garage Door, but use this MyQ device for both the switch and the sensor
  General clean up (eliminated most double blank lines, etc.)
