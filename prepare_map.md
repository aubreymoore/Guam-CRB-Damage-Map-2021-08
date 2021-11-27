# Preparing a Web Map

## Prep

Create a new directory and populate it with 2 files: 

* a copy of the previous QGIS CRB damage map project (to be used as a template)
* the survey SpatiaLite database (Guam05.db for example)

## Use previous map as a template

In QGIS, open the previous map project to use as a template. Save it under a new name. Example: 
```
Project | Save as | Guam05 | Save
```

## Change databases

In QGIS, in the Layers panel, left-click on each layer which gets data from the database, and update the database table source. Pay attention to which table the data comes from.

## Create webmap

* In QGIS, click on Web | Web map
* In the Export tab, choose export folder and export. For example, choose **~/Desktop/Guam-CRB-Damage-Map-2021-08**.  A new folder will be created with a name like **qgis2web_2021_11_27-07_20_53_797747**. 
* Rename the new folder to **webmap**

## Edit Webmap

* Run **edit_webmap.ipynb**. This will create a new file named **newindex.html**.
* Delete **index.html**.
* Rename **newindex.html** to **index.html**. 

## Update README.md

* Run **timeline_plot.ipynb** to update timeline plot.

## Update Press Release

* Grab a screenshot of the webmap.