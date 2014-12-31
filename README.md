win_mover
=========

A window resizer scripts for MacOS (you can resize your windows with an keyboard combination)
You can resize the current window to full screen size, or you can resize and move it on left half or right half screen part

this script should be used in combination with an external shortcut manager like Spark

basically, you can move/resize your windows using your keyboard like this:

![alt tag](https://raw.githubusercontent.com/jurgob/win_mover/master/readme_files/win_mover.gif)

##install it with Spark: 

checkout this project (from your terminal, type git clone https://github.com/jurgob/win_mover.git)
or download this project


download Spark: http://www.macupdate.com/app/mac/14352/spark

install Spark and launch it

double click on "AppleScript" on Spark's left menu

Copy and Paste one of the apple-scripts that you can find on the checkouted project)
(e.g. open MoveFull.scpt script, create a new shortcut naming it "MoveFull, copye and paste MoveFull.scpt and assign it to ctrl+alt+cmq+down-arrow, look the image bellow)

![alt tag](https://raw.githubusercontent.com/jurgob/win_mover/master/readme_files/create_shortcut_spark.png)

## first time usage:
on the first time you try to run the script, MacOs could rise an error.
To fix it you should go to "System Preferences" -> "security and Privacy" and then be sure that under "Accessibility" menu on "Privacy" tag "Spark Deamon" is checked". If it's not, press the padlock  and then check "Spark Deamon" voice

![alt tag](https://raw.githubusercontent.com/jurgob/win_mover/master/readme_files/privacy_settings.png)
