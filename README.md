# RfSP

## RenderMan for Substance Painter 24.4

This plugin exports your [Substance Painter](https://www.allegorithmic.com/products/substance-painter) project as one or more RenderManAsset.

RenderManAsset is the format used by the preset browser that was introduced in [RenderMan For Maya](https://rmanwiki.pixar.com/display/REN/RenderMan+for+Maya) 21.0. It allows for easy material setup interchange and includes dependencies like textures or OSL shaders.

![demo](img/rfsp.24.1.gif)

## Features

* Open the RenderMan Asset Browser directly in Substance Painter
* Export SP project to LamaSurface, PrxSurface or PxrDisney
* Support the following channels:
  * baseColor
  * metallic
  * roughness
  * normal
  * height
  * emission
  * anisotropylevel
  * anisotropyangle
  * scattering

## Requirements

This plugin requires the following software:

* Substance Painter 2021.1+, Adobe Substance 3D Painter
* RenderMan Pro Server 24.4+

## Install

* Download a zip archive from the github page
* Un-zip the archive
* Copy the 3 files inside the "plugin" folder directly in Substance Painter's python/plugins folder (do not copy the "plugin" folder in python/plugins).
  > OSX: `/Users/yourlogin/Documents/Substance Painter 2/python/plugins`

## Known Issues

* The progress dialog is temporarily a bit useless. This will be fixed in the next RenderMan version.
* The icons of the export dialog are clipped.
* The "import" item of the swatch's contextual menu should be disabled.
