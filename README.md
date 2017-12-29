# Real World Library 1.0 for X-Plane

## Library Structure Standardization

The goal of this project is to create a common X-Plane scenery library structure that any library developer can use to populate with their own creative works. This makes it easier for both the library builder, and for the scenery designer to populate and use the library.

"RealWorldLibrary" is the name of this standard. It is not the name used by a library author.

### Get The Structure

To download the structure you can either clone the GitHub repository 

git clone https://github.com/andyrooc/realworldlibrary

or download and unzip the zip file containing the structure from here:

https://github.com/andyrooc/realworldlibrary/tree/master/dist

After you have the structure on your disk, look for the **RealWorldLibrary** path. Rename this to your own library name, then copy it to your X-Plane Custom Scenery path.


e.g.:
*(windows cmd prompt)  

`cd realworldlibrary\src`  
`ren RealWorldLibrary JoesAircraftLibrary`  
`copy JoesAircraftLibrary "\X-Plane\Custom Scenery"`  

*(osx or Linux terminal prompt)  

`cd realworldlibrary/src`  
`mv RealWorldLibrary JoesAircraftLibrary`  
`cp JoesAircraftLibrary "~/X-Plane/Custom Scenery"`  

NOTE: While it is possible to replicate the structure purely through a properly compiled library.txt, and without using the structure for files, it is probably organisationally easier to use the structure for files as well, and it is easier for to use a tool to generate your library.txt    

## Standards & Conventions

Here we specify a few different ways you can help make your library more useable, and more popular by making it easy for scenery designers to find and use your creations.

**File naming convention.**

1. Avoid spaces in file names
2. Use camel case filenames (ie: Modern_Control_Tower.obj)
3. Use sizing in the filename where practical. i.e.:
    1. Large_Hangar.obj
    2. Small_Hangar.obj
    3. GA_Hangar_130x150x80f.obj   (width x length x height, f=feet, m=metres)

**Categorization**

There is a wide range of categories to place a file into, but it’s important to place the file into the right spot, and that the library reference uses that path.

You may feel the urge to add a new child path for you items, and this is a perfectly valid thing to do. However, make sure that it REALLY is needed, and if it really is, perhaps the path should be added to the RealWorldLibrary structure permanently. To make a new category or sub-category permanent, please raise an issue at https://github.com/andyrooc/realworldlibrary/issues

## Getting Going!

Update the readme.txt in the new library path to reflect the author name and library name and library version.
Add text files to the 'attributions' path to add any credit and licensing conditions.

Now you are ready to populate the structure with your creative works! Remember to update the library.txt file with references to your new creations.

Don’t worry about removing unpopulated paths as they will not affect X-Plane, X-Plane scenery designers or download size.
