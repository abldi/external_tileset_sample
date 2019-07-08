# External tileset sample
[Entry tileset example](https://github.com/abldi/external_tileset_sample/blob/master/README.md#entry-tilesetjson-example-with-two-external-tilesets-as-children)


### Entry tileset.json example with two external tilesets as children 

```
{
    "asset":{
        "generatetool":"cesiumlab@www.cesiumlab.com",
        "gltfUpAxis":"Z",
        "version":"1.0"
    },
    "properties":{
    },
    "geometricError": 200,
    "root":{
        "boundingVolume":{
            "region": [
                2.1197050411731104,
                0.5442527266222308,
                2.1207950411731104,
                0.5454927266222308,
                0,
                1000
              ]
        },
        "geometricError":75.9730159305084,
        "refine":"ADD",
        "children": [
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
                "uri": "0.json"
              }
            },
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
        ]
    }
}
```


### External tileset example with HLOD models
```
    {
    "asset":{
        "generatetool":"cesiumlab@www.cesiumlab.com",
        "gltfUpAxis":"Z",
        "version":"1.0"
    },
    "root":{
        "boundingVolume":{
            "region": [
                2.1197050411731104,
                0.5442527266222308,
                2.1207950411731104,
                0.5454927266222308,
                0,
                1000
              ]
        },
        "children":[     
            {
                "boundingVolume":{
                    "box":[
                        2.48768832185306,
                        -4.58087979024276,
                        10.8971535102464,
                        24.4194802122656,
                        0,
                        0,
                        0,
                        24.8279268313199,
                        0,
                        0,
                        0,
                        50.6109887245111
                    ]
                },
                "children":[
                    {
                        "boundingVolume":{
                            "box":[
                                2.48768832185306,
                                -4.58087979024276,
                                10.8971535102464,
                                24.4194802122656,
                                0,
                                0,
                                0,
                                24.8279268313199,
                                0,
                                0,
                                0,
                                50.6109887245111
                            ]
                        },
                        "children":[
                            {
                                "boundingVolume":{
                                    "box":[
                                        2.48768832185306,
                                        -4.58087979024276,
                                        10.8971535102464,
                                        24.4194802122656,
                                        0,
                                        0,
                                        0,
                                        24.8279268313199,
                                        0,
                                        0,
                                        0,
                                        50.6109887245111
                                    ]
                                },
                                "children":[
                                    {
                                        "boundingVolume":{
                                            "box":[
                                                2.48768832185306,
                                                -4.58087979024276,
                                                10.8971535102464,
                                                24.4194802122656,
                                                0,
                                                0,
                                                0,
                                                24.8279268313199,
                                                0,
                                                0,
                                                0,
                                                50.6109887245111
                                            ]
                                        },
                                        "children":[
                                            {
                                                "boundingVolume":{
                                                    "box":[
                                                        2.48768832185306,
                                                        -4.58087979024276,
                                                        10.8971535102464,
                                                        24.4194802122656,
                                                        0,
                                                        0,
                                                        0,
                                                        24.8279268313199,
                                                        0,
                                                        0,
                                                        0,
                                                        50.6109887245111
                                                    ]
                                                },
                                                "children":[
                                                    {
                                                        "boundingVolume":{
                                                            "box":[
                                                                2.48768832185306,
                                                                -4.58087979024276,
                                                                10.8971535102464,
                                                                24.4194802122656,
                                                                0,
                                                                0,
                                                                0,
                                                                24.8279268313199,
                                                                0,
                                                                0,
                                                                0,
                                                                50.6109887245111
                                                            ]
                                                        },
                                                        "children":[
                                                            {
                                                                "boundingVolume":{
                                                                    "box":[
                                                                        2.48768832185306,
                                                                        -4.58087979024276,
                                                                        10.8971535102464,
                                                                        24.4194802122656,
                                                                        0,
                                                                        0,
                                                                        0,
                                                                        24.8279268313199,
                                                                        0,
                                                                        0,
                                                                        0,
                                                                        50.6109887245111
                                                                    ]
                                                                },
                                                                "content":{
                                                                    "uri":"0/0/0/0/0/0/0/0.b3dm"
                                                                },
                                                                "geometricError":0,
                                                                "refine":"REPLACE",
                                                                "transform":[
                                                                    1,
                                                                    2.77555756156289e-17,
                                                                    0,
                                                                    0,
                                                                    -1.58340805351572e-17,
                                                                    1,
                                                                    -5.55111512312578e-17,
                                                                    0,
                                                                    -4.29325715976875e-17,
                                                                    0,
                                                                    1,
                                                                    0,
                                                                    0,
                                                                    0,
                                                                    0,
                                                                    1
                                                                ]
                                                            }
                                                        ],
                                                        "content":{
                                                            "uri":"0/0/0/0/0/0/0.b3dm"
                                                        },
                                                        "geometricError":0.0741923983696371,
                                                        "refine":"REPLACE",
                                                        "transform":[
                                                            1,
                                                            2.77555756156289e-17,
                                                            0,
                                                            0,
                                                            -1.58340805351572e-17,
                                                            1,
                                                            -5.55111512312578e-17,
                                                            0,
                                                            -4.29325715976875e-17,
                                                            0,
                                                            1,
                                                            0,
                                                            0,
                                                            0,
                                                            0,
                                                            1
                                                        ]
                                                    }
                                                ],
                                                "content":{
                                                    "uri":"0/0/0/0/0/0.b3dm"
                                                },
                                                "geometricError":0.296769593478548,
                                                "refine":"REPLACE",
                                                "transform":[
                                                    1,
                                                    2.77555756156289e-17,
                                                    0,
                                                    0,
                                                    -1.58340805351572e-17,
                                                    1,
                                                    -5.55111512312578e-17,
                                                    0,
                                                    -4.29325715976875e-17,
                                                    0,
                                                    1,
                                                    0,
                                                    0,
                                                    0,
                                                    0,
                                                    1
                                                ]
                                            }
                                        ],
                                        "content":{
                                            "uri":"0/0/0/0/0.b3dm"
                                        },
                                        "geometricError":1.18707837391419,
                                        "refine":"REPLACE",
                                        "transform":[
                                            1,
                                            2.77555756156289e-17,
                                            0,
                                            0,
                                            -1.58340805351572e-17,
                                            1,
                                            -5.55111512312578e-17,
                                            0,
                                            -4.29325715976875e-17,
                                            0,
                                            1,
                                            0,
                                            0,
                                            0,
                                            0,
                                            1
                                        ]
                                    }
                                ],
                                "content":{
                                    "uri":"0/0/0/0.b3dm"
                                },
                                "geometricError":4.74831349565677,
                                "refine":"REPLACE",
                                "transform":[
                                    1,
                                    2.77555756156289e-17,
                                    0,
                                    0,
                                    -1.58340805351572e-17,
                                    1,
                                    -5.55111512312578e-17,
                                    0,
                                    -4.29325715976875e-17,
                                    0,
                                    1,
                                    0,
                                    0,
                                    0,
                                    0,
                                    1
                                ]
                            }
                        ],
                        "content":{
                            "uri":"0/0/0.b3dm"
                        },
                        "geometricError":18.9932539826271,
                        "refine":"REPLACE",
                        "transform":[
                            1,
                            2.77555756156289e-17,
                            0,
                            0,
                            -1.58340805351572e-17,
                            1,
                            -5.55111512312578e-17,
                            0,
                            -4.29325715976875e-17,
                            0,
                            1,
                            0,
                            0,
                            0,
                            0,
                            1
                        ]
                    }
                ],
                "geometricError":75.9730159305084,
                "refine":"REPLACE",
                "transform":[
                    1,
                    2.77555756156289e-17,
                    0,
                    0,
                    -1.58340805351572e-17,
                    1,
                    -5.55111512312578e-17,
                    0,
                    -4.29325715976875e-17,
                    0,
                    1,
                    0,
                    0,
                    0,
                    0,
                    1
                ]
            }
        ],
        "geometricError":75.9730159305084,
        "refine":"REPLACE",
        "transform":[
            -0.852956218828698,
            -0.521982460204795,
            0,
            0,
            0.269135706351082,
            -0.439786759024323,
            0.856827624527703,
            0,
            -0.447248991422401,
            0.730836450805125,
            0.515602969198407,
            0,
            -2850081.22952981,
            4657234.09162181,
            3285664.97093417,
            1
        ]
    }
}

```



**Asset** contains Metadata about the entire tileset. Required.

```
    "asset":{
        "generatetool":"cesiumlab@www.cesiumlab.com",
        "gltfUpAxis":"Z",
        "version":"1.0"
```
    
**Properties,** a dictionary object of metadata about per-feature properties. Not required.
    
```
    "properties":{                        
    },  
```

**The geometricError** in meters, introduced if this tileset is not rendered. 

```
    "geometricError": 200,                
```

**Root,** a tile in a 3D Tiles tileset.
```
    "root":{                              
```  

A bounding volume defines the spatial extent enclosing a tile or a tile's content. The bounding volume types include an oriented bounding box, a bounding sphere, and a geographic region defined by minimum and maximum latitudes, longitudes, and heights.
    
```
    "boundingVolume":{ 
```

**Region** Array of six numbers that define the bounding geographic region with latitude, longitude, and height coordinates with the order.

```
    "region": [                      
        2.1197050411731104,        
        0.5442527266222308,
        2.1207950411731104,
        0.5454927266222308,
        0,
        1000
      ]
```


**geometricError** - model's Level of Details is determined by the distance of geometricError.
```      
        "geometricError":75.9730159305084, 
```      
    
**Refinement** determines the process by which a lower resolution parent tile renders when its higher resolution children are selected to be rendered. Permitted refinement types are replacement ("REPLACE") and additive ("ADD"). 
    
**"ADD"** the children are rendered in addition to the parent tile. 

**"REPLACE"** the children tiles are rendered in place of the parent, that is, the parent tile is no longer rendered.
        
```
        "refine":"ADD",                   
```

### Two external tilesets are defined here:

**BoundingVolume** of the external tileset.

**GeometricError** 

**Content:** 3D Tiles uses URIs to reference tile content. When the URI is relative, its base is always relative to the referring tileset JSON file
```
        "children": [
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
                "uri": "0.json"            
              }
            },
            
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
        ]
    }
}
```

### External tileset sample 

Includes required asset 

```
{
    "asset":{
        "generatetool":"cesiumlab@www.cesiumlab.com",
        "gltfUpAxis":"Z",
        "version":"1.0"
    },
```

boundingVolume of the external tileset.

```
    "root":{
        "boundingVolume":{
            "region": [
                2.1197050411731104,
                0.5442527266222308,
                2.1207950411731104,
                0.5454927266222308,
                0,
                1000
              ]
        },
        "children":[    
```

Model's hierarchy of LOD

```
            {
                "boundingVolume":{
                    "box":[
                        2.48768832185306,
                        -4.58087979024276,
                        10.8971535102464,
                        24.4194802122656,
                        0,
                        0,
                        0,
                        24.8279268313199,
                        0,
                        0,
                        0,
                        50.6109887245111
                    ]
                },
                "children":[
                    {
                        "boundingVolume":{
                            "box":[...]
                        },
                        "children":[...],
                        "content":{
                            "uri":"0/0/0.b3dm"
                        },
                        "geometricError":18.9932539826271,
                        "refine":"REPLACE",
                        "transform":[...]
                    }
                ],
                "geometricError":75.9730159305084,
                "refine":"REPLACE",
                "transform":[
                    ...
                ]
            }
        ],
        "geometricError":75.9730159305084,
        "refine":"REPLACE",
        
```

**The transform** property is a 4x4 affine transformation matrix, stored in column-major order, that transforms from the tile's local coordinate system to the parent tile's coordinate system—or the tileset's coordinate system in the case of the root tile.

```
        
        "transform":[
            -0.852956218828698,
            -0.521982460204795,
            0,
            0,
            0.269135706351082,
            -0.439786759024323,
            0.856827624527703,
            0,
            -0.447248991422401,
            0.730836450805125,
            0.515602969198407,
            0,
            -2850081.22952981,
            4657234.09162181,
            3285664.97093417,
            1
        ]
    }
}
```
