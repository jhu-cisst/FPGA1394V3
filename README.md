# FPGA1394V3
Design files for FPGA1394V3 board in Altium Designer format. The design files for the previous
revisions, Rev 1.x and and Rev 2.x, are in [this repository](https://github.com/jhu-cisst/FPGA1394).

The Rev 3.x design is based on the Xilinx Zynq System on Chip (SoC), XC7Z020, which includes an
FPGA (PL) and dual-core ARM processor (PS). The previous versions (Rev 1.x and 2.x) were based on
the Xilinx Spartan 6 FPGA. In addition, the Rev 3.x design contains two Ethernet ports, as compared
to one in Rev 2.x and none in Rev 1.x.

* `FPGA3.PrjPCB`: Altium Designer project file
* `Snn.SchDoc`: schematics (Altium Designer format)
* `FPGA3.PcbDoc`: PCB layout (Altium Designer format)
* `FPGA1394V3-Schematics.pdf`: PDF of schematics
* `FPGA1394V3-BOM.xlsx`: Bill of Materials (Microsoft Excel format)
* `Panel`: Subdirectory with panel design, including PCB fabrication and assembly files
 
## Release Notes

* Rev 3.0: Prototype design (3 boards built), design files not released
* Rev 3.1: Initial Release, Build #9 (107 boards)
