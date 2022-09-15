# Feathering in ArcGIS Pro
create the bounding AOI either using:

graphics:
- in Layout view, double click the data frame to “focus” it
- using the Rectangle tool on the Draw toolbar, draw a graphic that fills the extent of the page.
- switch to Data view and make the rectangle a little larger than the page extent using the handles to pull box out on opposite corners.
- switch back to Layout view.
- right click the data frame in the table of contents and click Convert Graphics to Features
- save in 207_carto named <iso3nnn>_carto_ext_py_s0_ma_pp.shp

shapefile
- create a new shapefile in 207_carto named <iso3nnn>_carto_ext_py_s0_ma_pp.shp
- zoom to suitable level in Layout view that you are happy is beyond what would be displayed if zoomed to country level
- start editing
- digitise a rectangle with an approx x / y ratio to the countries bounding box or template layout box
- save and stop editing
- run feathering.py
