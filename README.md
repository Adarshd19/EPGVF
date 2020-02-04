# EPGVF
 This repository contains the implementation of the edge preserving gradient vector field(EPGVF). You can see the working demos when EPGVF works for segmenting optic disc from fundus images along with affine snakes. 

- Authors : Adarsh Djeacoumar, Rohit Maheshwari, J. R. Harish Kumar, Chandra Sekhar Seelamantula.
- Code maintainer: J. R. Harish Kumar
- Email: harishj@iisc.ac.in, harish.jr@gmail.com, harishkumar.jr@manipal.edu

# ImageJ setup with Eclipse IDE
https://imagejdocu.tudor.lu/howto/plugins/the_imagej_eclipse_howto.
This link is for linking Eclipse IDE with ImageJ through which we run our code.
 
# Requirements
- ImageJ 1.51h or later on Java 1.7 (https://imagej.nih.gov/ij/docs/install/).
- Eclipse IDE with Version: Kepler Service Release 2 or later.
- Template Image (find Template_OD.tif file in Template_Image folder) to be saved in
“workspace/IJ” folder.

# Installation
- Add the “affine_snakes.class” file (find them in Java_ImageJ Class Files folder) into your ImageJ's plugins folder (path: workspace/IJ/plugins) irrespective of the OS specifications (Windows, Mac OSX, Linux).
- On restarting ImageJ, you will find a new entry named “Affine_Snakes” under the plugins menu (Plugins>Affine Snakes).
- Open any of the test optic disc images provided (find them in the Test_OD_Images folder) and then run the “Affine Snakes” plugin.

# Troubleshooting
* Error Message: java.lang.UnsupportedClassVersionError: Bad version number in .class file..." This error message pops up when the java version used for your ImageJ is not compatible
with the plugin. Please update the java version for your ImageJ software to a more recent version
* Error Message: java.lang.NoClassDefFoundError: path/to/javacv/javacv/jna/cxcore$".
This error appears if you did not put the system Independent class files into your ImageJ
plugins folder
* Error Message: java.lang.NullPointerException:
This error appears if you did not put the template image file “OD.tif” into the
workspace/IJ folder.

