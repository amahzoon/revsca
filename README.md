Copyright (c) 2019 Group of Computer Architecture. All Rights Reserved.



# RevSCA

This directory includes an executable of our tool RevSCA. For details on the techniques behind see the publication ["RevSCA: Using Reverse Engineering to Bring Light into Backward Rewriting for Big and Dirty Multipliers"](http://www.informatik.uni-bremen.de/agra/doc/konf/2019DAC_RevSCA.pdf) by Alireza Mahzoon, Daniel Große, and Rolf Drechsler published at DAC 2019.

RevSCA was developed and tested in Fedora 24. For related information, e.g. other SCA-based verification approaches, please visit http://www.sca-verification.org/ or contact revsca@sca-verification.org.


## How to use


```bash

./RevSCA <inputFile> <outputFile>

	inputFile:  name of an AIG file to read
	outputFile: name of output file containing verification data
```

## RevSCA-2.0 is now available at [GitHub](https://github.com/amahzoon/revsca2)!

RevSCA-2.0 features:

* The implementation has been improved significantly, thus RevSCA-2.0 is much faster.
* RevSCA-2.0 supports the verification of signed multipliers.
