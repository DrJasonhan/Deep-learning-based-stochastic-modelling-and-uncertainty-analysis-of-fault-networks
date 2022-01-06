# Deep-learning-based-stochastic-modelling-and-uncertainty-analysis-of-fault-networks

Name of the code/library: 
Contact: drjasonhan@163.com, +86 15822892267
Hardware requirements: Intel(R) Core(TM) i7-7700 CPU, 12.0G RAM 
Program language: Python
Software required: Windows 10
Program size: 274K

## File specification

The Data folder contains all the original data and the outputs. Among them, Data.3dm is the original data, Results.3dm is the final visualization.
The scripts contain two parts, including the modelling software-aid and deep learning part:

1. Modelling software part: Rhino-aided folder
   
   - The Rhino-aided/main.py is used to generate discretized fault networks that consist of random inner points.
   
   - The Rhino-aided/Verification.py is to verify the deep MDN.
   
   - The Rhino-aided/GenerateInnerPoints.py is used to generate the inner points of single faults.
   
   - The Rhino-aided/AddPoint.py is used to add 3D points into the Rhino software.
   
   - The Rhino-aided/ExtractPointPosition.py is used to read the positions of the point geometries in the Rhino software.

2. Deep learning part
   
   - The MDN.py is the built deep mixture density network.
   
   - The main.py is used to perceive the spatial distributions of faults and simulate faults.
   
   - The CodeSegments.py includes some scripts of diagram plotting.

## Brief usage

- Firstly, one should run the Rhino.exe and open the Data.3dm. 

- Then execute the Rhino-aided/main.py to generate the inner points. 

- Next, run the main.py to learn the distribution of the inner points, conduct the Chi-square test and randomly simulation, and build models with a certain confidence.

## Notice

The Sourcecode.zip is encrypted. Please contact Dr. Jason Han to get the password.
