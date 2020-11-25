Entity: Pattern  
===============







```yaml  
Pattern:    
  description: 'This entity contains a harmonised description of a generic pattern made for the Water Network Management domain. This entity is primarily associated with the water management vertical and related IoT applications.'    
  properties:    
    description:    
      properties: &pattern_-_properties_-_multipliers_-_properties    
        createdAt:    
          format: date-time    
          type: string    
        modifiedAt:    
          format: date-time    
          type: string    
        observedAt:    
          format: date-time    
          type: string    
        type:    
          enum:    
            - Property    
          type: string    
        unitCode:    
          type: string    
        value:    
          type:    
            - number    
            - string    
            - array    
      required: &pattern_-_properties_-_multipliers_-_required    
        - type    
        - value    
      type: object    
    multipliers:    
      properties: *pattern_-_properties_-_multipliers_-_properties    
      required: *pattern_-_properties_-_multipliers_-_required    
      type: object    
    startTime:    
      properties: *pattern_-_properties_-_multipliers_-_properties    
      required: *pattern_-_properties_-_multipliers_-_required    
      type: object    
    tag:    
      properties: *pattern_-_properties_-_multipliers_-_properties    
      required: *pattern_-_properties_-_multipliers_-_required    
      type: object    
    timeStep:    
      properties: *pattern_-_properties_-_multipliers_-_properties    
      required: *pattern_-_properties_-_multipliers_-_required    
      type: object    
    type:    
      description: 'NGSI-LD Entity Type'    
      enum:    
        - Pattern    
      type: string    
  required:    
    - id    
    - type    
    - multipliers    
    - timeStep    
    - startTime    
  type: object    
```  



    "id": "fbcb5fc8-8ca3-4533-a2eb-34bc89262190",  
    "type": "Pattern",  
    "multipliers": [  
        0.5692,  
        0.4647,  
        0.4385,  
        0.3604,  
        0.3098,  
        0.3345  
    ],  
    "timeStep": 3600,  
    "description": "Open Text",  
    "tag": "DMA1"  
}  
```  



    "id": "fbcb5fc8-8ca3-4533-a2eb-34bc89262190",  
    "type": "Pattern",  
    "multipliers": {  
        "value": [  
            0.5692,  
            0.4647,  
            0.4385,  
            0.3604,  
            0.3098,  
            0.3345  
        ]  
    },  
    "timeStep": {  
        "value": 3600  
    },  
    "description": {  
        "value": "Open Text"  
    },  
    "tag": {  
        "value": "DMA1"  
    }  
}  
```  



 "createdAt": "2020-02-20T17:43:00Z",  
 "description": "Open Text",  
 "id": "urn:ngsi-ld:Pattern:fbcb5fc8-8ca3-4533-a2eb-34bc89262190",  
 "modifiedAt": "2020-02-20T17:43:00Z",  
 "multipliers": [0.5692, 0.4647, 0.4385, 0.3604, 0.3098, 0.3345],  
 "startTime": "00:00",  
 "tag": "DMA1",  
 "timeStep": 3600,  
 "type": "Pattern"}  
```  



    "id": "urn:ngsi-ld:Pattern:fbcb5fc8-8ca3-4533-a2eb-34bc89262190",  
    "type": "Pattern",  
    "createdAt": "2020-02-20T17:43:00Z",  
    "modifiedAt": "2020-02-20T17:43:00Z",  
    "multipliers": {  
        "type": "Property",  
        "value": [0.5692, 0.4647, 0.4385, 0.3604, 0.3098, 0.3345],  
        "unitCode":"C62"  
    },  
    "timeStep": {  
        "type": "Property",  
        "value": 3600,  
        "unitCode": "SEC"  
    },  
    "description": {  
        "type": "Property",  
        "value": "Open Text"  
    },  
    "startTime": {  
        "type": "Property",  
        "value": "00:00"  
    },  
    "tag": {  
        "type": "Property",  
        "value": "DMA1"  
    },  
    "@context": [  
        "https://schema.lab.fiware.org/ld/context"  
    ]  
}  
```  