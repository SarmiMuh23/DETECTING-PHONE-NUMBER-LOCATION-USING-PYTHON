# DETECTING-PHONE-NUMBER-LOCATION-USING-PYTHON
This Python script utilizes various libraries to perform the following tasks:

It imports the phonenumbers library and a custom module myphone containing a phone number.
The script extracts geographic information and service provider details associated with the provided phone number.
It utilizes the geocoder and carrier modules from phonenumbers to obtain the location and service provider information, respectively.
The opencage.geocoder module is used to retrieve latitude and longitude coordinates based on the location information obtained earlier.
Using the obtained latitude and longitude, the script generates a map using the folium library.
It places a marker on the map at the specified coordinates with a popup displaying the location information.
Finally, the map is saved as an HTML file named "mylocation.html".
This script is designed to provide geographic information and visualize the location associated with a given phone number.
