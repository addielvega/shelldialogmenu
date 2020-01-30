# shelldialogmenu


The script uses a while loop with a constant true value to create an endless loop displaying the menu dialog. After every function, the script returns to displaying the menu. Because the while loop exiting is done by the break command to jump out of the loop. The menu dialog includes a cancel button to exit as well. 

The script uses the mktemp command to create two temporary files for holding data for the dialog commands. The first one, $temp, is used to hold the output of df, whoson, and memusage commands to display in the textbox dialog. The second temporary file, $temp2, hols the selection value from the main dialog menu.  
