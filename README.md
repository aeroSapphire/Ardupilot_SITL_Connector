# ArduPilot SIL Connector for Simulink

Simulink C++ S-function for software-in-the-loop simulation with ArduPilot.

[![View ArduPilot software-in-the-loop (SIL) connector for Simulink on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://uk.mathworks.com/matlabcentral/fileexchange/114315-ardupilot-software-in-the-loop-sil-connector-for-simulink)

Requirements
- MATLAB & Simulink (MATLAB R2022a or earlier)
- MinGW-w64 or MSVC C/C++ Compiler
- MissionPlanner

Files

[ardupilot_sil_connector.cpp](https://github.com/aviumtechnologies/ardupilot-sil-connector/blob/master/ardupilot_sil_connector.cpp)
<div style="height:1px; background-color:rgba(0,0,0,0.12);"></div>

[make.m](https://github.com/aviumtechnologies/ardupilot-sil-connector/blob/master/make.m)
<div style="height:1px; background-color:rgba(0,0,0,0.12);"></div>

[includes.zip](https://github.com/aviumtechnologies/ardupilot-sil-connector/blob/master/includes.zip) (contains the Asio C++ library)
<div style="height:1px; background-color:rgba(0,0,0,0.12);"></div>

Build instructions

-  Install MATLAB-supported compiler  
https://mathworks.com/support/requirements/supported-compilers.html.
-  Download the "ardupilot_sil_connector.cpp" and "make.m" files and the "includes.zip" archive.
-  Unzip the "includes.zip archive".
-  Run "make.m" to create a "ardupilot_sil_connector.mexw64" (Windows), "ardupilot_sil_connector.mexa64" (Linux), "ardupilot_sil_connector.mexmaci64" (macOS) file.
