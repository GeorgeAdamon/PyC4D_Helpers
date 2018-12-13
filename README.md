# PyC4D_Helpers
A list of useful python functions and resources for Cinema4D. 
This repository aims to be a concentrated collection of useful scripts for common everyday C4D problems.
Hopefully at some point we won't have to dig into old posts in forums anymore.

Topics covered so far:
  - UserData Handling (adding, removing, searching, setting)
  - Material and Shader Creation
  - Hierarchy Navigation (Selecting, Deselecting, Selecting Children etc)
  - [OBJ Sequence Importing](https://github.com/GeorgeAdamon/pyc4d_helpers/tree/master/scripts/ObjSequenceReader)
  - [Importing Transformation Matrices From Other Software](https://github.com/GeorgeAdamon/pyc4d_helpers/tree/master/scripts/RhinoMatrixLoader)

### Installation Notes
In order to be able to use the pyc4d_helpers functions inside Cinema4D, you need to Copy / Paste the **pyc4d_helpers** folder in: 

* For versions prior to R20: *Your Cinema4D Preferences Folder* / library / python / packages / *your operating system*
* For R20 or later: *Your Cinema4D Preferences Folder* /python27/libs

Example R19: 
```
C:\Users\George\AppData\Roaming\MAXON\Cinema 4D R19_BFE04C39\library\python\packages\win64\
```
Example R20: 
```
C:\Users\George\AppData\Roaming\MAXON\Cinema 4D R20_4FA5020E\python27\libs
```
