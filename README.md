# deepanshu
Final approach 
The STL file mesh data consists of the face data and vertices data
The vertices are in the format (x,y,z) while the face data is in the format (x1,y1,z1),(x2,y2,z2),(x3,y3,z3). Depicting which particular vertices will be used to make a face.
The stl file contains this data in binary as well as ascii format.
Created a code on jupyter that extracts face data and vertices data using the numpy-stl library.
The code will automatically download the face and vertices data in csv format.
Then these files are used in another jupiter code that used build123d library to read the data and create and stl file 

Working
open the code (face and vertices extraction code) and upload the given stl file in the jupyter directory (content) and paste its path in the code. then run the code.
face and vertices data in csv format will be downloaded.
open the code (mesh build123d) on jupyter which uses build123d library to recteate the stl file  
the code has to be executed cell by cell starting from cell2
cell 2 will ask the user to upload first vertices data and then face data.
after cell2 running each cell will generate a display of the stl (mesh_output) and ultimately download the same.

volumetric
the properties of the generated file and the given file were compared in fusion360 
The volume of the input and generated file were same.
