# IconMapArchive
A repository that contains previous releases of deprecated [Icon Map visual for Power BI](https://www.icon-map.com/).

**Icon Map was a free custom visual for Microsoft Power BI - it is no longer being developed or supported. If you need an actively maintained and supported map visual for Power BI, consider [Icon Map Pro](https://iconmappro.com/), which offers enhanced features and dedicated support.**

-----------------------------------------

# Releases Info (From the [Icon Map Downloads page](https://www.icon-map.com/downloads.html) before deletion)

## Icon Map V3 - visual
#### 22nd September 2023 - [Icon Map 3.3.2](https://github.com/HadiFadl/IconMapArchive/blob/main/3.3.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.3.2.1.pbiviz) (test version - runs in parallel with version from AppSource)

* Added the ability to set the level of grayscale applied to background layer
* Added the ability to set the transparency of the background layer
* Fixed an issue when the auto zoom is disabled by the user using the override zoom control where the map would zoom out of datapoints after clearing the selection
(bug) Lasso tool no longer works with vector tile layers. This will be fixed in the next release.

#### 25th August 2023 - [Icon Map 3.3.1](https://github.com/HadiFadl/IconMapArchive/blob/main/3.3.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.3.1.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Resolved fill and border transparency settings not working
* Added ability to add multiple fields to tooltips (adding custom tooltip fields removes the default tooltip)
* Added the ability to render an image at the end of a WKT linestring
* Added ability to drill down multiple vector tile layers, and set the URL using conditional formatting
* Fix for tooltips not clearing on zooming or moving off item
* Groundwork for multiple additional new features

#### 19th April 2023 - [Icon Map 3.2.17](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.17.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Added striped fills to the formatting options.

#### 29th March 2023 - [Icon Map 3.2.16](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.16.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Added ability to display GeoJSON shapes stored within the Power BI dataset. These are added in the same way as WKT content. The visual now supports a mixture of GeoJSON, WKT and images stored in the dataset.

#### 22nd March 2023 - [Icon Map 3.2.15](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.15.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Added a control to allow report viewers to override the auto zoom to data points feature.

#### 20th March 2023 - [Icon Map 3.2.14](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.14.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Added the ability to change geoJSON URLs using conditional formatting

#### 9th March 2023 - [Icon Map 3.2.13](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.13.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Resolved issue with OpenRailMaps no longer displaying

#### 5th March 2023 - [Icon Map 3.2.12](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.12.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Improved geodesic line behaviour. For previous implementation, select 'Curved' instead of 'Geodesic'

#### 4th March 2023 - [Icon Map 3.2.11](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.11.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Fixed bug preventing "Auto zoom to items selected on the map" from working with WKT objects

#### 3rd March 2023 - [Icon Map 3.2.10](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.10.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Added control to measure distances on the map.

#### 3rd March 2023 - [Icon Map 3.2.9](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.9.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Fixed issue for daylight terminator not working with specified date and time.

#### 3rd March 2023 - [Icon Map 3.2.8](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.8.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Requires Power BI Desktop October 2022 or later
* Updated to Power BI Visuals API 5.1.0
* Added conditional formatting to WMS transparency
* Prevented map zooming on double click on pinch when "Lock Zoom" setting enabled.

#### 17th September 2022 - [Icon Map 3.2.6](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBBx.3.2.6.0.pbiviz) (test version - runs in parallel with version from AppSource)

* Fixed modern tooltips
* Changes to WMS to support authentication parameters on the querystring
* Changed transparent option TRUE to uppercase on WMS URLs for better compatibility with ESRI services

#### 10th June 2022 - [Icon Map 3.2.4](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.2.4.0.pbiviz)

* Added open to include line intersecs on lasso select (currently only items entirely within lasso area are included)
* Added missing formatting options that were hidden when "Explicit" image size was selected
* Fixed bug where lines weren't correctly extending the map bounds for auto zoom
* Improved tolerance to poorly formatted WKT objects
* Added ability to set custom overlay transparency
* Fixed bug with expression based formatting of tooltips, whereby a null value would crash the visual

#### April 2022 - Icon Map 3.2.3]

* Refactored source code to improve readability - no changes to functionality

#### 16th March 2022 - [Icon Map 3.2.2](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.2.2.0.pbiviz)

* Added ability to draw objects when size field contains a null value

#### 31st January 2022 - [Icon Map 3.2.1](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.2.1.0.pbiviz)

* Removed wmflabs background layers as these are no longer available for use.

#### 2nd January 2022 - [Icon Map 3.2.0](https://github.com/HadiFadl/IconMapArchive/blob/main/3.2.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.2.0.pbiviz)

* Release for App Source
* Updated http link to https for Icon Map support site

#### 20th Decmber 2021 - [Icon Map 3.1.17 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.17.pbiviz)

* Removed some debug output
* Reinstated GeoJSON inactive formatting options that had been removed in error

#### 6th Decmber 2021 - [Icon Map 3.1.16 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.16.pbiviz)

* Added highlighting support for vector tile layers
* Added auto zoom capbility for vector tile layers with long lats provided
* Added more flexibility around spacing in WKT
* Fixed a bug related to zooming when only a single item present

#### 24th October 2021 - [Icon Map 3.1.15 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.15.pbiviz)

* Allow WKT shapes with shape types in non-capital letters.
* Added initial support for vector tiles
* Fixed bug preventing flip Y axis setting on Simple CRS functioning with WKT objects

#### 21st October 2021 - [Icon Map 3.1.14 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.14.pbiviz)

* Added warning icon revealing error message when a layer errors when being added.
* Added additional text on GeoJSON loading error message - most problems with GeoJSON are down to CORS
* Added warning icon revealing error message when invalid geoJSON is provided.
* Fixed a bug where previous objects remained when map filtered to show no objects (further investigation needed for impact on GeoJSON)
* Fixed a bug where if the map zoom is locked - it was still possible to use the scroll wheel to zoom

#### 12th October 2021 - [Icon Map 3.1.13 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.13.pbiviz)

* Fixed bug preventing drilldown from working with alternative CRS

#### 9th October 2021 - [Icon Map 3.1.12 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.12.pbiviz)

* Fix for bug preventing multipoint WKT objects being sized

#### 2nd October 2021 - [Icon Map 3.1.11 beta](https://github.com/HadiFadl/IconMapArchive/blob/main/3.1.x/iconMapV34089C0EB522B416294AA926F71B4FDBB.3.1.11.pbiviz)

* Changed processing of WKT data. Should provide increased performance handling different projections
* Added ability to include GeoJSON data in wkt field. (experimental)
* Replaced processing of geodesic lines

#### 13th September 2021 - Icon Map 3.1.10 beta

* Fixed bug preventing map from rendering when null size values are present
* Added ability to set image width and height independently when "Explicit" selected as size type in "Objects" settings

#### 12th September 2021 - Icon Map 3.1.9 beta

* Added support for Power BI modern tooltips
* Updated to Power BI Visuals API 3.8.3
* Fixed a bug related to auto zooming inactive shapes in GeoJSON layers preventing the map from rendering
* Performance increase selecting large number of map objects

#### 24th August 2021 - Icon Map 3.1.8 beta

* Fixed an issue when clearing expression based formatting values not returning to use manual setting

#### 24th August 2021 - Icon Map 3.1.7 beta

* Fixed an bug with geoJSON layers that cleared map on cross highlighting

#### 23rd August 2021 - Icon Map 3.1.6 beta

* Fixed an bug that prevented the min and max zoom settings for the inbuilt map backgrounds being respected

#### 17th August 2021 - Icon Map 3.1.5 beta

* Added Lock Map in zoom settings to prevent dragging the map
* Reduced default zoom increment from 1 to 0.5

#### 13th August 2021 - Icon Map 3.1.4 beta

* Added support for points within GeoJSON files
* Added built in support for EPSG3006 and EPSG3009 in the CRS settings

#### 9th August 2021 - Icon Map 3.1.3 beta

* Aligned the text used for the map backgrounds with those shown in the dropdown for easier use with expression based formatting
* Fixed a bug where the default map location wasn't being restored on report load

#### 30th July 2021 - Icon Map 3.1.2 beta

* Added Flip Y axis option for Simple CRS for coordinates that start at the top left, rather than the bottom left
* Restored the min and max zoom options to the CRS menu for Simple CRS

#### 29th July 2021 - Icon Map 3.1.1 beta

* Fixed bug where lines weren't immediately removed from the map when the destination coordinates were removed from the field well
* Fixed bug where circles weren't immediately removed from the map when the coordinates were removed from the field well
* Fixed bug where a WMS layer wasn't removed from the map when switched to off, but the URL remains in the settings
* Fixed bug where the map didn't render correctly or auto zoom where there was one POINT WKT object
* Fixed bug where "No Fill" was selected as the fill or border color, the map didn't render
* Fixed bug "Zoom Map" couldn't be set to 'yes', after it had been set to 'no'
* Changed the behaviour of auto zoom when only one item. It now only uses the Zoom on Single Item value if it's a circle or point. More complex objects use the object bounds

#### 21st July 2021 - Icon Map 3.1.0 beta

* Removed Line / Border width field and moved it to expression based formatting in the formatting options
* Removed Image Rotation field and moved it to expression based formatting in the objects formatting options
* Added expression based formatting to the transparency options
* Added EPSN 27700 as a CRS
* Added the ability to provide custom CRS using Proj4 (experimental)
* Added support for map tiles with custom CRS
* Added support for WMS tiles with custom CRS
* Added support for circles, images, geoJSON and WKT objects with custom CRS

#### 13th July 2021 - Icon Map 3.0.9 alpha

* Fixed bug with empty line widths preventing map from rendering

#### 7th July 2021 - Icon Map 3.0.8 alpha

* Fixed bug with setting items as selectable
* Added ability to select some additional coordinate systems
* Added XY coordinate system and image background layer
* Added shift and control keys as additive select (not yet working on lasso)
* Added the ability to set the zoom increment when using the + - buttons

#### 17 June 2021 - Icon Map 3.0.7 alpha

* Added ability to draw a 2nd image at the line destination coordinates

#### 10 June 2021 - Icon Map 3.0.6 alpha

* Fixed bug with drilldown on geoJSON layers
* Fixed bug combining images and circles
* Fixed bug preventing rendering with combinations of WKT / GeoJSON and Circles and/or images

#### 09 June 2021 - Icon Map 3.0.5 alpha

* Fixed bug preventing any images showing when a null rotation value was present
* Added ability to set zoom level when only a single zoomable item is present

#### 06 June 2021 - Icon Map 3.0.4 alpha

* Updated to latest Power BI visuals API (3.8.1)
* Added ability to use Icon Map with multiselection with other report visuals
* Added tooltip text to formatting options
* Prevented HTML in map labels from user input
* Map position and zoom persisted when auto zoom not enabled
* Split out background layers and overlays
* Added open railway map and open sea map layers
* Resolved issue with WKT point and multipoint

#### 17 May 2021 - Icon Map 3.0.1 alpha

* Initial release
