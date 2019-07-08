# External tileset sample

### Main entry **tileset.json**

**Asset** contains Metadata about the entire tileset. Required.

```
{
    "asset":{
        "generatetool":"cesiumlab@www.cesiumlab.com",
        "gltfUpAxis":"Z",
        "version":"1.0"
    },
    
    "properties":{                        //A dictionary object of metadata about per-feature properties. Not required.
    },   
    
    "geometricError": 200,                //The error, in meters, introduced if this tileset is not rendered. 
    
    "root":{                              // A tile in a 3D Tiles tileset.
    
        "boundingVolume":{                // A bounding volume defines the spatial extent enclosing a tile or a tile's                                                   // content. The bounding volume types include an oriented bounding box, a bounding                                             // sphere, and a geographic region defined by minimum and maximum latitudes,                                                   // longitudes, and heights.

            "region": [                   // array of six numbers that define the bounding geographic region with latitude,   
                2.1197050411731104,       // longitude, and height coordinates with the order
                0.5442527266222308,
                2.1207950411731104,
                0.5454927266222308,
                0,
                1000
              ]
        },
        
        "geometricError":75.9730159305084, // Model's Level of Details is determined by the distance of geometricError.
        "refine":"ADD",                    // Refinement determines the process by which a lower resolution parent tile                                                  // renders when its higher resolution children are selected to be rendered. 
                                           // Permitted refinement types are replacement ("REPLACE") and additive ("ADD").
                                           // "ADD" the children are rendered in addition to the parent tile
                                           // "REPLACE" the children tiles are rendered in place of the parent, that is, the                                              //  parent tile is no longer rendered.
        
        "children": [
       
       // external tileset #1 defined here:
       
            {
              "boundingVolume": {
                "region": [
                    2.1197050411731104,
                    0.5442527266222308,
                    2.1207950411731104,
                    0.5454927266222308,
                    0,
                    1000
                ]
              },
              "geometricError": 0,
              "content": {
                "uri": "0.json"             //3D Tiles uses URIs to reference tile content. When the URI is relative, its base                                             //is always relative to the referring tileset JSON file
              }
            },
            
            
         // START external tileset #2:
                   
            {
              "boundingVolume": {
                "region": [
                    2.1197050411731104,
                    0.5442527266222308,
                    2.1207950411731104,
                    0.5454927266222308,
                    0,
                    1000
                ]
              },
              "geometricError": 0,
              "content": {
                "uri": "1.json"
              }
            }
            
        // END external tileset # 2
            
        ]
    }
}
```
