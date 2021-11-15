# Simple HTTP Server and CLient for sending files

In order for the files to work correctly the server must be started before the client. The directory the server is in must have an empty LiPD file and the directory the client is in must have a NetCDF file, since we are only testing the functionality of the **Flask** Library 

The ```server.py``` file uses the **Flask** library to start an HTTP server at the current directory, reads the LiPD file(s) from the client, and then returns a NetCDF file

The ```client.py``` file sends a post request containing the LiPD file in a dictionary and then prints the NetCDF file it recieved
 
