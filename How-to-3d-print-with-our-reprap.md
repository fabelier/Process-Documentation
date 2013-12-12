HOW TO 3D PRINT @fabelier 
==========

### Software to model the piece

* Solid works : pro 
* sketch up + stl plug in : intermediate
* 123d (autocad) : newbies
* Openscad : geeky (you can script !!! super cool )



### Processus

* Check that the power supply is ON
* Export your object into STL file
* Open slicer 
	* home / bin/ slicer/bin / slic3r 
* Drag and drop the STL object into slicer 
* Don't touch the print  setting (normaly setup by @Alex + @kevin)
* Check the layer thinkness print 
	* Print Setting/ infill / Fill Desnsity : 0.30 = 30%
	* Print Setting/ layers > horizontal shell
* Plater > export GCODE file
* Open Pronterface : home/bin/printrun/pronterface.py (Lady gaga on youtube)
	* click on "Run"
* Click on connect 
* Check the "home" of all axes X,Y,Z 
	* if you have a calibration problem check with @kevin @Alex
* Click on "monitor printer" 
* Position Z axes on +10
* Click on the button "set" in front of label "bed" (plateaux)
* Click on the button "set" in front of label "heater" (tete d'impression)
* It's ready when "bed" and "heater" are at "bed" and "heater" target
* Load the GCODE file
* Check estimed duration 
* Check extrusion before print : 
	* Click on extrude button (bottom left)
	* Check if the extrusion happening 
	* Clean the extrusion 
* Print button 
* Wait and see ...

------------


Others notes
==========
>> Attention : epaisseur 
>> Slicer : convertie le stl en language machine (g code)
>>> transforme objet 
>> export STL 

