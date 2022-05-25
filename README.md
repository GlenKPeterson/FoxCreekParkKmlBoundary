# FoxCreekParkKmlBoundary
I had to manually alter the KML file downloaded from Google Maps in order for iNaturalist to upload it without complaint.
I'm adding it to source control so I can diff versions if I ever have to change it.
I used IntelliJ as an XML editor and told it that the `.kml` file is a type of XML.
The two required XSD files are included, so you can validate before uploading.
iNaturalist seemed to require the following nodes (I'm doing a lot of guessing here):
 - Document/Placemark/Polygon/outerBoundaryIs/LinearRing/coordinates
 - Document/Placemark/Point/Coordinates (maybe)

Map on Google from which the original fcp.kml file was downloaded:
https://www.google.com/maps/d/edit?mid=1jkpOl_RORxUw37tNo9VdU9URGh8K6dx2&ll=35.60864850775076%2C-82.38844466440862&z=19

iNaturalist Place created with the manually altered fcp.kml file:
https://www.inaturalist.org/places/fox-creek-park

iNaturalist Project that uses that Place:
https://www.inaturalist.org/projects/fox-creek-park-species-survey

Park website:
https://foxcreekpark.org/

KML FAQ:
https://developers.google.com/kml/faq

## Change Log

### 2022-05-25: "Plus 3 Meters"
Added approximately 3 meters to the border for GPS inaccuracy at Allen's request.
This is no longer intended to represent the boundaries of the park, but just to make
any observations made within the margin of GPS accuracy of the park show up in the park's project.
Apologies to any neighbors who are posting their yard-life to iNaturalist and don't want it to appear as part of the park.
If you are such a neighbor, and are bothered, please let us know so we can do something to accommodate you.