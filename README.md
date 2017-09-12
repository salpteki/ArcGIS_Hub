# ArcGIS_Hub

{
  "type": "grouped",
  "datasets": [
    {
      "url": "https://services1.arcgis.com/0n2NelSAfR7gTkr1/ArcGIS/rest/services/Vacant_Lots/FeatureServer/0",
      "query": {
        "groupByFieldsForStatistics": "Split",
        "outStatistics": [
          {
            "statisticType": "sum",
            "onStatisticField": "Split",
            "outStatisticFieldName": "Split_Total"
          }
        ]
      }
    }
  ],
  "series": [
    {
      "category": {
        "field": "Split",
        "label": "something funny"
      },
      "value": {
        "field": "Split_Total",
        "label": "Reuse as a Split Lot"
      }
    }
  ]
}
