BHT Series Sample Program Guideline
                                                                    Feb.4, 2013
Source file name: stktake.src

1. Introduction
To the users of this sample program
DENSO WAVE INCORPORATED retains the copyright to this source code, but allows users to use it, in whole or in part, and make modifications without prior permission of DENSO WAVE INCORPORATED. DENSO WAVE INCORPORATED shall not, however, be held responsible for any damages arising from such use or modifications.

2. General Description
This sample program is developed mainly for stock-taking for the BHT Series scanners. In applications using this sample program, the BHT reads the bar code printed on the provided sample sheet, compiles the read data in the memory, and then transmits so far accumulated data to the host computer in a batch.

This is a basic program with essential features required for the BHT Series scanners to read bar code data (key entry also allowed), display a product name by referring to the master file, upload the compiled data and download the master data.

3. Operating Conditions
  This sample program is supported by the following BHT Series scanners.
      BHT-300 Series
      BHT-500 Series
      BHT-600 Series
      BHT-800 Series
      BHT-900 Series
  The compiler should be the BHT-BASIC3.5 or later. 

4. How to Use
  Turn on the BHT and the following menu screen appears. 
  +----------------+
  |   * Menu *     |
  |1:Take  2:Send  |
  |3:Check 4:Master|
  |                |
  |                |
  |>select [1]-[4] |
  +----------------+
 
