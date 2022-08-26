# IAEAphspToH5phsp
A tool to convert IAEA phase space file to H5 phase space file owned to G4Linac_MT code. 

<b> How to compile it </b>

1. unzip the file IAEAphspToH5phsp.tar.xz in your local drive, create a new directory called "build" nearby "IAEAphspToH5phsp" folder.

2. download the IAEA routines from http://www-nds.iaea.org/phsp

3. change the current directory to IAEAphspToH5phsp and copy into it this files :

iaea_header(.cc && .hh) iaea_phsp(.cc && .hh) iaea_record(.cc && .hh) utilities(.cc && .hh)

4. change the current directory to build folder then type:

cmake  ../IAEAphspToH5phsp


make 


<b> How to use it </b>
1. copy IAEA phase space file to the build folder.
2. Run: ./IAEAphspToH5phsp nameOfIAEAPhspWitotFileExtension


Example


elbakkali@elbakkali-Workstation:~/Desktop/BUILD$ ./IAEAphspToH5phsp test

=== Calling IAEAPhsp-->H5Phsp tool. 

===  IAEAPhsp-->H5Phsp converter: Phsp file path  is   test

===  IAEAPhsp-->H5Phsp converter: Total number of primary events is 50000.

===  IAEAPhsp-->H5Phsp converter: Number of primary active events is 6964.

===  IAEAPhsp-->H5Phsp converter: Active events percent (%)  is 13.928.

===  IAEAPhsp-->H5Phsp converter: Number of photons in Phsp  is 5958.

===  IAEAPhsp-->H5Phsp converter: Number of electrons in Phsp  is 2232.

===  IAEAPhsp-->H5Phsp converter: Number of positrons in Phsp  is 3.

===  IAEAPhsp-->H5Phsp converter: Number of neutrons in Phsp  is 0.

===  IAEAPhsp-->H5Phsp converter: Number of protons in Phsp  is 0.

===  IAEAPhsp-->H5Phsp converter: Convertion is done succussfully.

elbakkali@elbakkali-Workstation:~/Desktop/BUILD$ 




<b> I want a help  </b>

Contact me at my email address bahmedj@gmail.com.

 

<b> License </b>

This software is free software; you can redistribute it and / or modify
it under the terms of the GNU General Public License as published by the
Free Software Foundation; either version 2 of the License, or (at your
option) any later version.

For the complete text of the license see the GPL-web
page.

