# REST

## Assignment:
Add (through code) a feature to the FeatureLayer with the following URL<br/>
https://services8.arcgis.com/pJN5OprYGVml9ZCV/ArcGIS/rest/services/DIP_Rest_Public/FeatureServer/0

See if your action resulted in a dot on the map on:<br/>
https://www.arcgis.com/apps/mapviewer/index.html?webmap=d1e96ad9e7fe4b36b3f9d20b4134bfa2

---
The structure of an ArcGIS Feature in JSON is:

```JSON
{
    "attributes":{
        "fieldname1":"stringValue1",
        "fieldname2":"stringValue2",
        "fieldname3":42,
        etc
        etc
    },
    "geometry":{
        "x":lon,
        "y":lat,
        "spatialReference":{"wkid":4326}
    }
}
```
---
## Challenge:
1. Using the Python API or the REST API with the language of your choice
2. Search in ArcGIS Online for the webmap with title: “Gemeente TestMap” of “Gemeente TestMap BE” from owner: “devteamesrinl”
3. Copy the webmap to your own content
4. Filter the layer on your own area
5. Save the webmap

---
## Resources:
Feature object:<br/>
https://developers.arcgis.com/documentation/common-data-types/feature-object.htm

Add Features:<br/>
https://developers.arcgis.com/rest/services-reference/enterprise/add-features.htm