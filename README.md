# NPS QGIS Map Templates

QGIS Print Composer templates with National Park Service graphics branding.

QGIS, or Quantum GIS, is a cross-platform Open Source geographic information system. This repository contains a collection of QGIS print composer templates which are themed per the National Park Service (NPS) Graphics Identity Program. These will enable NPS staff to quickly produce finished, graphics compliant maps using QGIS.

The templates were manually ported by Lava Beds National Monument Natural Resource Management from a collection of similar ArcGIS 10 templates originally produced by the Intermountain GIS Program Office.


## Usage

0. Download the .ZIP archive containing template files and their supporting images: https://github.com/nationalparkservice/NPS-QGIS-Map-Templates/archive/master.zip

1. Unzip and copy the .QPT template files and supporting `resources` to a location on your computer.

2. In QGIS, select Project -> Composer Manager

3. Under the "New From Template" heading, select "Specific"; then click "..." to browse to the folder where you saved the templates, and choose a specific template by name. Finally click "Add" to add a new print composer based on this template for your project. You may optionally give it a name (for example, "8.5x11 Landscape").

4. Due to the limited templating capability of QGIS, you may need to make the following initial changes:

  A. The NPS Arrowhead Logo in the upper right corner may show as a red "X". Click the item name "NPS Arrowhead Logo", the "Item Properties" tab, and the "Main Properties" section. Click "..." under the heading "Image Source", and browse to the `resources` folder alongside your templates; select the arrowhead .SVG file.

  B. The North Arrow may show as a red "X". Click the "North Arrow" item name and follow the steps above, choosing the north arrow .SVG file.

5. Customize! http://docs.qgis.org/2.8/en/docs/user_manual/print_composer/print_composer.html

  A. Add a map.

  B. Click the Scale Bar and hit the "delete" key. You should now add a new scalebar at the same location. This is unfortunately necessary so that QGIS will autoscale the size and units per your custom map; the scalebar in the template won't autoadjust. We recommend changing the scalebar font size to '8', line width (under "Display") to 0.6mm, and left segments to '0'.

  C. Update the Map Title, Subtitle, the name of your NPS unit, map date, and list of data sources utilized.

  D. Continue adding any of your own custom map components, such as a legend, images, data tables, etc.


## License

As a work of the United States Government, this project is in the public domain within the United States.

Additionally, we waive copyright and related rights in the work worldwide through the CC0 1.0 Universal public domain dedication.


## Author

David A. Riggs  
Physical Science Technician  
Lava Beds National Monument  
email: david_a_riggs at nps dot gov
