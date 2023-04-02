..
  SPDX-License-Identifier: BSD-3-Clause
  Copyright Contributors to the OpenEXR Project.

Stereo Images
#############

This directory contains three different versions of a single scene
split into four separate passes, as well as the combined result as a
regular image for comparison.

In each case, ``Leaves.exr``, ``Trunk.exr``, ``Ground.exr`` and
``Balls.exr`` are individual deep passes.

Stereo
======

Left and right views of each image, at 1920x1080 (Full HD)
resolution. This folder also contains a composited, flattened, image,
with separate views and depth channel, as a regular "scanlineimage"
EXR.  The composited image has four separate parts.

LeftView
========

Only the left view of each image, at 1920x1080 (Full HD) resolution.


LowResLeftView
==============

Only the left view, downsampled by decimation to 1024x576 (there is a
visible shift in the image compared to the 1920x1080 images) This
folder also contains a composited, flattened image, with no depth
channel, as a regular "scanlineimage" EXR.

