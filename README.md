# perthmap_property_prices_bubbles
This map shows Perth Metro area with bubbles overlaid as median property prices(2017) and change in(%) between 2016 and 2017 for each suburb.



To see visualization in the browser check this https://bl.ocks.org/olgabradford/a0543ac36651eab394fe117580679baa

# Design

Geojson file of all WA suburbs was downloaded from https://data.gov.au/dataset/wa-suburb-locality-boundaries-psma-administrative-boundaries
Than boundaries of suburbs were simplified (resampled) to achieve a smaller size of a file with (http://mapshaper.org/)
Mapshaper.org is a handy free online tool that allows to upload a geojson file, display it as a map, then choose one of three simplification alogrithims which can adjust the strength of with a slider. So, WA MAP  path was simplified without loosing too much detail for quicker visualization purposes. Only Perth Metropolitan suburbs + Mandurah are displayed in current visualization.



# Data sources
GEOJSON map of WA suburbs is from https://data.gov.au/dataset/wa-suburb-locality-boundaries-psma-administrative-boundaries
Median house prices and changes in house prices  in %  are from REIWA 

