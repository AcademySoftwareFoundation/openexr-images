..
  SPDX-License-Identifier: BSD-3-Clause
  Copyright Contributors to the OpenEXR Project.

Multi-View Images
#################

Multi-view OpenEXR images with a number of formatting variations (scan
lines vs. tiles, image channels, etc.).  All images contain at least a
left-eye and a right-eye view suitable for presentation on a stereo
display.  The images have been prepared for viewing with a pixel
density of approximately 100 pixels per inch; the width of the
displayed images should be about 5 to 10 inches (12 to 25 cm).

.. list-table::
   :align: left
           
   * - ``Balls.exr``

     - scan lines; R, G, B channels; 2 views; default view is left

   * - ``LosPadres.exr``

     - scan lines; R, G, B channels; 2 views; default view is right

   * - ``Adjuster.exr``

     - scan lines; R, G, B channels; 3 views; default view is center


   * - ``Fog.exr``

     - scan lines; Y luminance channel only; 2 views; default view is left

   * - ``Impact.exr``

     - tiled mip-map;  R, G, B channels; 2 views; default view is left


