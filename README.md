# Higher-Order Functions and JSON

## Objectives

* Use Map, Filter, and Reduce functions to mine data from a JSON file.

## Instructions

Write your code in `hof.js`.

`volcano.json` contains a data set of 804 historical volcanic eruptions.  Below is a sample of the data for each eruption.

```JSON
  {
    "Year": 2017,
    "TSU": "",
    "EQ": "",
    "Name": "Kilauea",
    "Location": "Hawaiian Is",
    "Country": "United States",
    "Latitude": 19.425,
    "Longitude": -155.292,
    "Elevation": 1222,
    "Type": "Shield volcano",
    "VEI": "",
    "Agent": "",
    "DEATHS": 1
  }
```

Use `filter`, `map`, `reduce` and any other higher-order functions to analyze the data in the following ways:

1. Return the volcanoes that erupted in the 1970s.
2. Return an array of the names of volcanoes that had an eruption with a Volcanic Explosivity Index (VEI) of 7 or higher.
3. Return the eruption with the highest number of recorded deaths.
4. Return the percentage of eruptions that caused mudflows (Agent_Code "M" for Mudflow).
5. Return the most common type of volcano in the set.

Extra Practice

6. Return the number of eruptions when supplied a country as an argument.
7. Return the average elevation of all eruptions.
8. Return an array of types of volcanoes
9. Return the percentage of eruptions that occurred in the Northern Hemisphere.
10. Return the names of eruptions that occurred after 1900, that did NOT cause a mudflow, happened in the Southern Hemisphere, and had a VEI of 5.
11. Return the names of eruptions that occurred at or above an elevation passed in as an argument.
12. Return the agents of death for the ten most deadly eruptions.


### References

Volcano data retrieved from: National Geophysical Data Center / World Data Service (NGDC/WDS): Significant Volcanic Eruptions Database. National Geophysical Data Center, NOAA. [doi:10.7289/V5JW8BSH](https://data.nodc.noaa.gov/cgi-bin/iso?id=gov.noaa.ngdc.mgg.hazards:G10147)
