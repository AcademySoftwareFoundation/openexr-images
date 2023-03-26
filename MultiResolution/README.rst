..
  SPDX-License-Identifier: BSD-3-Clause
  Copyright Contributors to the OpenEXR Project.

Multi-Resolution Images
#######################

Various multi-resolution OpenEXR images.

Regular Images
==============

.. list-table::
   :align: left
           
   * - ``Bonita.exr``		
 
     - Point Bonita in the Marin Headlands, California (mip-map)

   * - ``Kapaa.exr``

     - Near Kapa'a, Kaua'i, Hawai'i (rip-map)

Environment Map Images
======================

.. list-table::
   :align: left
           
   * - ``KernerEnvCube.exr``
       
     - Parking lot on Kerner Blvd., San Rafael, California (mip-map, in
       cube-face format)

   * - ``KernerEnvLatLong.exr``

     - Parking lot on Kerner Blvd., San Rafael, California (mip-map, in
       latitude-longitude format)

   * - ``StageEnvCube.exr``

     - Stage with props, cameras and other equipment (mip-map, in
       cube-face format)

   * - ``StageEnvLatLong.exr``

     - Stage with props, cameras and other equipment (mip-map, in
       latitude-longitude format)

   * - ``OrientationCube.exr``

     - An environment map, in cube-face format, that indicates the
       directions of the environment's x, y and z axes.

   * - ``OrientationLatLong.exr``
    
     - An environment map, in latitude-longitude format, that
       indicates the directions of the environment's x, y and z axes.

   * - ``WavyLinesCube.exr``

     - An environment map, in cube-face format, that can be used to
       test how an application program, for example, a 3D renderer,
       handles the seams of environment maps.

       The environment image contains multiple sets of wavy lines.
       Each set consists of three parallel lines of equal width.
       Parts of the middle line run along one of the map's seams,
       crossing back and forth over the seam.  In a cube-face map,
       seams occur along the edges of the six faces of the cube. 

       If the environment map is correctly projected onto a sphere,
       then the seams should be invisible, and all lines should appear
       to have the same uniform width everywhere.  It should be
       impossible or at least difficult to tell where the middle line
       in each set crosses one of the map's seams.

   * - ``WavyLinesLatLong.exr``
    
     - An environment map, in latitude-longitude format, that can be
       used to test how an application program, for example, a 3D
       renderer, handles the seams of environment maps.

       The environment image contains multiple sets of wavy lines.
       Each set consists of three parallel lines of equal width.
       Parts of the middle line run along one of the map's seams,
       crossing back and forth over the seam.  In a latitude-longitude
       map, there is a seam along the meridian with longitude +/-pi.

       If the environment map is correctly projected onto a sphere,
       then the seams should be invisible, and all lines should appear
       to have the same uniform width everywhere.  It should be
       impossible or at least difficult to tell where the middle line
       in each set crosses one of the map's seams.

   * - ``WavyLinesSphere.exr``

       This image shows what the ``WavyLinesCube.exr`` and
       ``WavyLinesLatLong.exr`` environment map should look like when
       has been correctly projected onto a sphere.  In this image the
       environment sphere is seen from the outside, not from the
       inside.

Mip-Map Images
==============

.. list-table::
   :align: left
           
   * - ``ColorCodedLevels.exr``
    
     - A mip-map checkerboard image where each resolution level has a
       different color.  If this image is used to texture an object
       during 3D rendering, then the color of the object shows which
       resolution levels are accessed by the renderer as it projects
       the texture onto the object.

   * - ``PeriodicPattern.exr``	

     - A mip-map image that tiles seamlessly in "periodic" wrap mode.
       The image can be used to check if 3D renderers correctly
       implement this wrap mode.

   * - ``MirrorPattern.exr``	
    
     - Mip-map images that tile seamlessly in "mirror"
       wrap mode.  The image can be used to check if 3D
       renderers correctly implement this wrap modes.

