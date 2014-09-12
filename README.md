#lasercut-delta

## Intro

This repo contains a design for 3D a delta-stlye printer, largely built from laser-cut parts. The motivation being a fast-to create printer, accessible to anyone with access to a laser cutter.

Parts are glued together to form final assemblies. If you've ever built an old-school balsa aircraft, you'll be right at home

There is also a [list of other parts](VITAMINS.md) to complete the printer and a [few notes on designing for laser cut parts](LESSONS.md) which I've jotted down.

## Editing

All files are authored using [QCad](http://www.qcad.org/en/) which has proven to work really well for this kind of 2D editing

## Design
The printer is a conventional delta layout. Under active development. Either toothed belt or spectra fishing line can be used

##Arms
Both designs are intended to use magnetic balls glued to the effector and carriages, with bolts in aluminium tubing acting as the arms. 

##HotEnd
The effector is designed to work with the [E3D V6 HotEnd][1], but others can easily be accomodated

##Printing/Cutting
The printer is designed to be cut from 3mm MDF sheet. In all DFX files, later 0 is designed to be cut. All other layers should be hidden/ignored for cutting.

The largest parts currently are the base and top sheets, which have a maximum length of 335mm by 290mm, meaning that it ought to fit onto an A3 laser cutter.

##Status
Currently the body parts and some bearing carriages are cut and assembled. The next step is to finish the bearing carriages and assemble the effector.

[1]: http://e3d-online.com/E3D-v6
