# NodeOSC 2.0
OSC support for nodes and general usage.

Please be aware: Version 2 is breaking NodeOsc settings from version 1. Pleas look at the wiki for more infos

This add-on does not require any other add-on to work.

Currently it has node support for
* [Animation Nodes](https://animation-nodes.com/)
* [Sorcar](https://blender-addons.org/sorcar-addon/)

## Download

latest release from [here](https://github.com/maybites/blender.NodeOSC/releases/latest)

## Usage

please visit the [wiki](https://github.com/maybites/blender.NodeOSC/wiki) for more info.

### Video Tutorial

<a href="https://youtu.be/o9bzujeOyc8" target="_blank"><img src="http://img.youtube.com/vi/o9bzujeOyc8/0.jpg"
alt="NodeOSC Part One" width="240" height="180" border="10" /></a>

## Credits

written by maybites (2021)

heavily inspired by and code used from http://www.jpfep.net/pages/addosc/ and http://www.jpfep.net/pages/addroutes/.

NodeOSC relies on

* the pure [python module](https://pypi.org/project/oscpy/) [oscPy](https://github.com/kivy/oscpy) (by Kivy).
* the pure [python module](https://pypi.org/project/python-osc/) [python-osc](https://github.com/attwad/python-osc) (by Attwad).


## ChangeLog

### V2.0.0
Added dynamic evaluation format functionality combined with loops. Inspired by functionality introduced in http://www.jpfep.net/pages/addroutes/. Code cleanup and improved user interface.

### V1.0.9
Added the neat operator I found in http://www.jpfep.net/pages/addroutes/ to create new osc handlers from the context menu while hovering over a user element.

### V1.0.8
Allows to execute function calls with datapath. for example: bpy.ops.screen.animation_play(). values passed on with osc message are ignored.

### V1.0.6
Fixed (hopefully) the reference of the dynamic link library for liblo.

### V1.0.5
It plays now nice if liblo library is not installed

### V1.0.4
Moved the transformation of AnimationNodes datatype DoubleList into the node.

### V1.0.3
Added AnimationNodes datatype DoubleList to be able to send via OscNumber node.
