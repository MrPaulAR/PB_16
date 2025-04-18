# Copyright and Disclaimer
Copyright: Scott Hanson

This documentation describes Open Hardware and is licensed under the CERN Open Hardware License Version 2 - Strongly Reciprocal. (CERN-OHL-S)

You may redistribute and modify this documentation under the terms of the CERN OHL-S-v2 (https://ohwr.org/cern_ohl_s_v2.txt). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v2-S for applicable conditions

**Under CERN OHL-S-v2, derivative work must be publicly released as defined in subsection 3.3**

# Receiver Out SMD

The "Receiver Out SMD" is a 4 port Differental Reciver output board for the PB16. This design is surface mount based. All the design files are open source and available on github.

### Version 3
Version 3 (2025-2-23) adds an Attiny1616 Micro controller and Test Button to enable local testing. This is be programmed with the included Ardunio INO file or hex file. Requires a UPDI programmer. This can be bypassed by populateding R12 with 10K.

### Ordering
To order PCBs upload the "GERBER-Receiver_Out.zip" file in the "jlcpcb\production_files" folder. Enable the SMD service, 'BOM-Receiver_Out.csv' is the SMD BOM and 'POS-Receiver_Out.csv' is the SMD CPL position file.

## [Part BOM](https://github.com/computergeek1507/PB_16/raw/master/Receiver_Out_SMD/Receiver_Out_BOM.ods)

![Image of Receiver Out](https://github.com/computergeek1507/PB_16/raw/master/Receiver_Out_SMD/Receiver_Out.png)

