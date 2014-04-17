EdgeBlendingCompositions
========================

EdgeBlending resources created with Quartz Composer for use with 2 or 3 screens in VDMX5

# The Files

VidVox forum user **[bAjA](http://www.vidvox.net/forums/memberlist.php?mode=viewprofile&u=832)** created a quartz patch for edge blending, you can [find the original source link here](http://www.vidvox.net/forums/viewtopic.php?t=5863)

The file is included here unaltered for your convenience:

[Three Screens Edge Blending by bAjA] (edgeBlend-three-screens.qtz)

I adjusted it for two screens:

[Two Screens Edge Blending] (edgeBlend-two-screens.qtz)

# Simple VDMX5 edge blending tutorial

## VDMX Preferences
1. Download the files
2. Open VDMX5 Preferences > User Paths
3. Under "VDMX Resources" select "Show in Finder"

![VDMX Preferences][1]

   [1]: images/1.png

## Adding the compositions to VDMXs library

  * Navigate to the folder "qcFX"
  * Copy the files here

![Adding the compositions to VDMXs library][2]

   [2]: images/2.png

## Setting up edge blending in VDMX

  * restart VDMX5
  * In the Workspace Inspector select "Canvas/Main Output"
  * In the Canvas/Main Output FX panel click the "Load Asset" dropdown.
  * select "Misc. QC > edgeblend-two-screens (or edgeblend-three-screens)"

![Setting up edge blending in VDMX][3]

   [3]: images/3.png

## In use

  * Use the "pixelblend" slider to adjust the amount of blending and adjust to match your overlapping projectors

VDMX output window with pixelblend at 0:

![pixelblend at 0][4]

	[4]: images/5.png


VDMX output window with pixelblend at 100:

![pixelblend at 100][5]

   [5]: images/4.png
