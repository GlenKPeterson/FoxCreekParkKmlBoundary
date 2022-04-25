# FoxCreekParkKmlBoundary
I had to manually alter the KML file downloaded from Google Maps in order for iNaturalist to upload it without complaint.
I'm adding it to source control so I can diff versions if I ever have to change it.
I used IntelliJ as an XML editor.
The two required XSD files are included, so you can validate before uploading.
iNaturalist seemed to require the following nodes (I'm doing a lot of guessing here):
 - Document/Placemark/Polygon/outerBoundaryIs/LinearRing/coordinates
 - Document/Placemark/Point/Coordinates (maybe)

Map on Google from which the original KML file was downloaded:
https://www.google.com/maps/d/edit?mid=1jkpOl_RORxUw37tNo9VdU9URGh8K6dx2&ll=35.60864850775076%2C-82.38844466440862&z=19

iNaturalist Place created with this KML file:
https://www.inaturalist.org/places/fox-creek-park

iNaturalist Project that uses that Place:
https://www.inaturalist.org/projects/fox-creek-park-species-survey

Park website:
https://foxcreekpark.org/

KML FAQ:
https://developers.google.com/kml/faq
