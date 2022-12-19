# GEVolImport

## Summary: This module imports VOL files output by the GE tome microCT scanner into 3D Slicer. It parses the PCR file to obtain the 3D image dimensions, voxel spacing, data format and other relevant metadata about the VOL file and generate a NHDR file to load the VOL file into Slicer.

## To install 
Clone the VolImportModule repository to your computer (or use the download zip option). Then open 3D Slicer application, and go to **Edit->Application Settings->Modules**. Click the >> button next to **Additional Module Path** and click Add, and navigate to the folder you cloned (or unzipped) the VolImportModule. Restart Slicer for changes to take effect. 

## Usage
After restarting SLicer hit **CTRL+F** and search for VolImport module and switch to the module. Click `...` button to and navigate to the **XXXXX.pcr** file, where XXXXX is the name of the VOL file you would like to import. Hit the Generate NHDR button, this will create a NHDR file for you in the same directory of the PCR and VOL files to be able to load the volume next time, as well as immediately loading it into the active scene. **For module to work correctly, the accompanying VOL file and the output NHDR file should sit in the same folder as the PCR file.** 
