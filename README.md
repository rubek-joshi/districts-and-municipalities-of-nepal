# Districts and Municipalities of Nepal

It is difficult to obtain data in Nepal. Even more difficult obtaining accurate data in a convenient way. This repository has been created for the sole purpose of sharing convenient data of the districts and municipalities of Nepal.

The data is stored conveniently in a JSON format and is **authentic** as of the **date of the latest commit**. PR's to improve this data further will be entertained.

## JSON Format
```json
[
  {
    "district" : "districtName",
    "metropolis" : [
      "metropolisName"
    ],
    "municipalities" : [
      "municipalityName",
      "municipalityName"
    ],
    "rural-municipalities" : [
      "ruralMunicipalityName",
      "ruralMunicipalityName"
    ]
  },
  {
    "district" : "districtName",
    "sub-metropolis" : [
      "subMetropolisName",
      "subMetropolisName"
    ],
    "municipalities" : [
      "municipalityName",
      "municipalityName"
    ],
    "rural-municipalities" : [
      "ruralMunicipalityName",
      "ruralMunicipalityName"
    ]
  },
  {
    "district" : "districtName",
    "municipalities" : [
      "municipalityName",
      "municipalityName"
    ],
    "rural-municipalities" : [
      "ruralMunicipalityName",
      "ruralMunicipalityName"
    ]
  }
]
```
