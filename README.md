# myMultiDimAmr
An attempt to solve the dynamicMeshing of OpenFOAMv1812

## Issue
The dynamicMesh tool of OpenFOAMv1812 is not working properly. This is going to be solved by editing the source code of OpenFOAMv1812 by copying the source code of OpenFOAMv5x.

## Changes to the previous dynamicMeshing
- The **adaptCriteria class** was deleted and substituted by the OpenFOAMv5x **mutliCritRefinement**
- This change came along with changes to the different **hexRef classes**

## On going issues
- 3D dynamicMeshing still needs to be edited
- The balancing could show some problems

