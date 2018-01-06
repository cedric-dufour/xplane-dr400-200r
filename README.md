ROBIN DR400-200R (GPL) FOR X-PLANE
==================================
By Cédric Dufour <cedric.dufour@ced-network.net>
(see the licensing section below for licensing details)

  ![DR400-200R](dr400_icon.png)

Based on the existing HB-KDY, from the 'Groupe Vol à Moteur (GVM) de Sion'
(Switzerland):

 * 200CV injection engine
 * Variable pitch (constant RPM) propeller
 * Auxiliary fuel tank (set "Fuel XFR" to "L" to transfer to main tank)
 * Working 2D and 3D cockpit, with all instruments required for "at-home"
   training
 * High-resolution (2048x2048) textures (resize to 1024x1024 if experiencing
   GPU performances problems)
 * Customized airfoils
 * Tuned to match real-life experience as closely as possible (in regards with
   weight and balance, performances, and aerodynamical behavior)
 * French and English checklists provided (PDF format, courtesy of GVM; please
   see the CHECKLIST.DISCLAIMER)
 * Including all "source" files (from/for JavaFoil, XFoil, Blender, Gimp; ~38MB)

TODO:

 * Improve the 3D interior model (pilot, 3D details, better textures, etc.)
 * Improve whatever else needs to
 * Contributors are welcome!


THE AUTHOR DISCLAIMER
---------------------

This aircraft does not aim towards being a 100% photo-realistically faithful
model, but rather towards an "operationnally" faithful replica, allowing DR400s
pilots to train "at-home" (practicing their checklist, checking a flight plan
against the plane performances, etc.).

That being said, I hope you will still enjoy it!


INSTALLATION
------------

 1. Copy this entire folder within X-Plane's folder (ideally within a custom
    'Aircraft/My Aircrafts' folder, to prevent X-Plane's Updater to overwrite it)

 2. Load the aircraft using X-Plane's standard procedure


FLYING HOWTO
------------
(shortly put)

### Engine start and take-off

#### Engine start

 * Battery and alternator "on" [lower left corner]
 * Cowl flaps open (down) [middle handle]
 * Propeller full RPM [blue handle]
 * Mixture "on" (full rich) [lower center red handle]
 * Throttle 10-20% [left or right middle handle]
 * Magnetos "ign" (then "both") [lower left corner]
 * Avionics and lights "on" [top right corner]

#### Take-off

 * Flaps 15°
 * Trim elevator (white sector) [lower center wheel]
 * Release brakes
 * Throttle 100%
 * "Lighten the wheel" at 50 knots (IAS)
 * "Lift-off" at 60 knots (IAS)

#### Initial climb

 * Speed 70 knots (IAS)
 * MP: 25" (Throttle), RPM: 2'500 (Propeller), FF (Mixture): 12 gal/h
 * 1'000ft above ground level (AGL): flaps up

#### Climb

 * Speed 80 knots (IAS)

### Level-off and cruise

 * Cowl flaps closed (up)
 * MP: 23" (Throttle), RPM: 2'400 (Propeller), FF (Mixture): 11 gal/h

### Landing and engine shut-down (shortly put)

#### Downwind

 * Mixture "full rich"
 * Speed in "white sector"
 * Flaps 15° down
 * Speed 80 knots (IAS)

#### Final

 * Flaps 60° down
 * Speed 70 knots + half of head-wind (IAS)
 * Propeller full RPM [blue handle]

#### Runway threshold

 * Throttle 0%
 * Flare and land

#### Engine shut-down

 * Mixture "off" (full lean) [lower center red handle]
 * Magnetos "off" [lower left corner]
 * Battery and alternator "off" [lower left corner]


DESIGN
------

This aircraft has been created entirely from scratch, based on the author's
experience and knowledge of the Robin DR400, along with information gathered
throughout the documentation (aircraft flight manual, weight and balance
sheet, etc.) of the genuine aircraft, and material publicly available on the
Internet.

The airfoils and their characteristics (lift, drag and moment polars) have
been created using JavaFoil, XFLR5/XFoil and TransFoil (see the acknowledgments
section below for further details). Some "guessing" had to be done concerning
the choice of some profiles, because of the lack of available information
in this regards.
(see the ./source folder for JavaFoil's geometry and XFoil's polar data files)

The aircraft characteristics (cf. X-Plane Plane Maker) have been derived from
the aircraft's flight manuals (various versions) and "fine-tuned" (sometimes
deviating from the actual value) in order to have the aircraft behave in
X-Plane as closely as possible as in the real life (see the REALISM file for
further details).

The 3D model was created using X-Plane's Plane-Maker and Blender.
(see the ./source folder for Blender's source files)

All textures were created using Gimp, based on pictures from the Robin DR400s
belonging to the 'Groupe Vol à Moteur (GVM) de Sion' (Switzerland).
(see the ./source folder for Gimp's source files)


ACKNOWLEDGMENTS
---------------

I would like to acknowledge and give my thanks to all those who made it
possible to create and distribute this aircraft:

 * Martin Hepperle and its JavaFoil airfoil design applet
   ( http://www.mh-aerotools.de/airfoils/ )

 * Mark Drela and all other developers of the XFoil airfoil analysis program
   ( http://web.mit.edu/drela/Public/web/xfoil/ )

 * X-Andre and all other contributors to the XFLR5 airfoil (XFoil-based)
   analysis program.
   ( http://xflr5.sourceforge.net/ )

 * Lance Prior and its FoilTrans airfoil polars translator program for X-Plane
   ( http://forums.x-plane.org/index.php?app=downloads&showfile=7896 )

 * All the members of the development team of the Blender 3D modeling program
   ( http://www.blender.org/ )

 * Marginal and its 'Xplane2Blender' import/export plug-in
   ( http://www.marginal.org.uk/x-planescenery/tools.html )

 * All the members of the development team of the Gimp image editing program
   ( http://www.gimp.org/ )

 * All the members of the development team of Audacity sound editing program
   ( http://audacity.sourceforge.net/ )

 * Austin Meyer and all the members of the development team of X-Plane, without
   whom we would not have so much fun
   ( http://www.x-plane.com/ )

 * danklaue and his wonderful video tutorials on Plane-Maker and Blender
   ( http://www.youtube.com/user/danklaue )

 * All the members and contributors of the X-Plane community and forums, for
   their valuable comments and insights
   ( http://www.x-plane.org/ )

 * My fellows from the 'Groupe Vol à Moteur (GVM) de Sion' (Switzerland), for
   their valuable comments, insights and patience (when dealing with the real-
   life DR400!)
   ( http://www.gvm-sion.ch/ )


LICENSING
---------

The Robin DR400-200R (GPL) for X-Plane may be used, modified and redistributed
under the terms of the

  **GNU General Public License (GPL) version 2**

(see the COPYRIGHT and LICENSE.GPLv2 files).

The Robin DR400-200R (GPL) for X-Plane includes all resources listed in
the CHANGELOG file. All contributors should make sure to update the CHANGELOG
file appropriately, by listing the files they modified or added along their
name (and e-mail address).

Other resources are (and must be) used according to their original license,
which is (should be made) available from their respective author.

