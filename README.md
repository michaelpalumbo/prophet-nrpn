# Install
1. In the Live *Places* section, add a new folder and select this directory.

	![](./add_folder.png)


## Adding parameters
Open the file "prophet\_6\_param_table.txt" in a text editor.



go to page 79 or 80 of the supplied pdf "Prophet-6-OM.pdf", find the param you want to add, then add it to the text file. the format has to be exactly how I did it, so for example NRPN 4 from that manual page is "OSC 1 Pulse Width", which has a value range of 0-255. You'd add a new line in the text file and type:

4, 0 255 "OSC 1 Pulse Width";

Don't forget the semi colon at the end :)

Save the file. the device should reload the text file shortly after.

