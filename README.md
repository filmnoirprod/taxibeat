# Τaxibeat
Taxibeat is an application written in Java and Prolog . It's main purpose is to find the closest taxi to the client's coordinates . After finding the closest taxi the application tries to find the best route to the client's destination filtering informations such as traffic , traffic lights , open roads , rush hour , accidents etc.
This application was impelented as part of the Artificial Intelligence course (7th semester) for the National Technical University of Athens.


## Input data 
The actual input data : map coordinates , streets and road information such as road lanes , traffic jam , road direction etc are part of the https://www.openstreetmap.org dataset .

### Application Launch and time efficiency 
Below you can find an example of usage of the current application . In order to run this application you should of course compile it using javac . After this just type : java nodes.csv client.csv taxis.csv example2 in a terminal window . In the above execution command (which stands as an example) nodes.csv stands as the map file which contains the coordinates of our nodes , client.csv stands as the file with the coordinates of client , taxis.csv stands as the file with the coordinates of the available taxis and example2 stands as the name of the output file (kml) . The output file will be a map with the sortest available routes from all taxis to the client . In every output file the green route stands for the closest taxi route to the client .

![alt text](https://github.com/filmnoirprod/taxibeat/blob/master/images/runt.jpg)
