Beamspring (low profile) CAD resources
======================================

CAD data for reproduction/modifications of IBM's beamspring switches from the 70's. Based on measurements of original components, draft angles omitted for now.

Project thread: https://deskthority.net/viewtopic.php?f=7&t=21925

beamoriginal: original housing made in FC0.17
beamlowprofile: low profile switch assembly
beamlowprofileWIP: WIP files (changes could break assembly constraints)

Gerber output process:
Generate cross-section, export result as dxf, import dxf in pcbnew (kicad), plot gerber



Requirements
------------
FreeCAD 0.18 and A2plus addon (Tools>Addon manager)


License
-------
Public domain


TODO
----
- Recreate and refine original switch as a2plus/a3 assembly
