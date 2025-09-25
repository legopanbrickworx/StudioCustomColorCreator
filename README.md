Lego Pan BrickWorx' Bricklink Studio Custom Color Generator v2.0.1

Copyright (C) 2025  Lego Pan BrickWorx/Paul Lavallee

------------------------------------------------------------------------------------

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

For inquiry, please email legopanbrickworx@gmail.com

------------------------------------------------------------------------------------

LegoPan Brickworx Bricklink Stud.io Custom Color Generator for Windows version 2.0.1

Thanks to Petrus G for your help finding the details on file locations and what to
change in order to create these custom colors and inspiring me to write a script to
automate the process! You know who you are :)

Thanks also to Unpixelled for their great research and documentation on Stud.io 
colors and their use!

------------------------------------------------------------------------------------

This script file is designed to create and add custom colors to Bricklink Stud.io.

***Currently it only works to create solid colors, metallic colors, chrome colors, 
and rubber colors, not transparent or other special color types. This may be added 
in future versions*** 

------------------------------------------------------------------------------------

To use:

Simply run the RUNME shortcut which will launch the CustomColorCreator.bat as an 
administrator. Answer the prompts to create your custom color.

***If the RUNME shortcut fails to launch, right-click on the CustomColorCreator.bat
file and select "Run as Administrator" to run the script properly***

The user will be asked to select a color type (Currently only solid, metallic, 
chrome, and rubber colors are supported), next, enter a HEX color code for your 
color, then give your new color a name.

Once the variables are entered, the script will backup your current configuration 
files to C:\temp\studiocolortemp\ in case of any issues or errors during the 
installation of the new color.

The script will then compile the needed entries and rename your color to 
"ColorType-Custom-Your_color_name" so that you can simply search Stud.io for 
"Custom" in the color list to easily find it.

It will then apply the newly compiled configuration files to the current Stud.io
configuration files and add the new color.

A new unique color ID number will be generated based on the color type and HEX color 
code entered which can then be checked if the user tries to make another color with
the same type and HEX color code in the future. If so, the script will ask if the 
user would like to rename the old color to avoid conflicting color IDs in Stud.io

Thats it! The script will automatically complete the entire process!


LegoPan BrickWorx
