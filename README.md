
Copyright (c) 2019 Group of Computer Architecture.
All Rights Reserved.

This directory includes an executable of our tool RevSCA. For details on the techniques behind see the publication "RevSCA: Using Reverse Engineering to Bring Light into Backward Rewriting for Big and Dirty Multipliers" by Alireza Mahzoon, Daniel Große, and Rolf Drechsler accepted at DAC 2019.

RevSCA was developed and tested in Fedora 24. For related information, e.g. other SCA-based verification approaches, please visit http://www.sca-verification.org/ or contact revsca@sca-verification.org.


*************************************************


Use the following command to verify multiplier:

	./RevSCA <inputFile> <outputFile>


inputFile:  name of an AIG file to read

outputFile: name of output file containing verification data
