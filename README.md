# Simple HTTP Server and CLient for sending files

In order to run the code you must have an empty LiPD file saved in the same location as the files, as well as a NetCDF file to reutrn saved in the same directory since this was only used to test the **Flask** Library.

The *server.py* file uses the **Flask** library to start an HTTP server at the current directory, reads the LiPD file(s) from the client, and then returns a NetCDF file

The *client.py* file sends a post request containing the LiPD file in a dictionary and then prints the NetCDF file it recieved
 
