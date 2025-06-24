# egui EasyMark editor porting to Bevy (Unofficial)

## Overview

This is a self-study project to learn egui, bevy, and bevy_egui.

Original egui EasyMark editor source code:
https://github.com/emilk/egui/tree/main/crates/egui_demo_lib/src/easy_mark

Bevy Engine:
https://github.com/bevyengine/bevy

bevy_egui:
https://github.com/vladbat00/bevy_egui

Code porting is mostly done by google Jules AI, directed by ddbaker.

The latest commit is only tested on Windows 11.

## Preserved git branches

"work-in-progress' git branches are intentionally preserved for study purpose.
The coding progressed from git branch  `easy_mark_port_attempt_1` to `6`, then `jules/debug-blank-viewer-attempt`.
Jules was having difficulty to resolve "blank render pane" problem, but eventually resulved after trials and errors.
It took certain time, but I was impressed by Jules' step-by-step approach. It worked in the end. `easy_mark_port_attempt_7` was used just for some minor final touch by ddbaker.

## known isssue

* The primary window is having difficulty to move across multi-display. The same sypmtom can be observed with bare Bevy example codes.