# ArduPilot SIL Connector for Simulink

Simulink C++ S-function for software-in-the-loop simulation with ArduPilot.

[![View ArduPilot software-in-the-loop (SIL) connector for Simulink on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://uk.mathworks.com/matlabcentral/fileexchange/114315-ardupilot-software-in-the-loop-sil-connector-for-simulink)

## Requirements ##
    1. Windows 10/11
    2. MSVC C/C++ (recommended) or MinGW-w64 compiler
    3. MATLAB & Simulink (MATLAB R2022a or later)

## Compiler Installation and MEX Setup

You can install the Visual Studio Community Edition. During the installation, make sure to include the **"Desktop development with C++"**, which includes the necessary tools for MATLAB compatibility. After installation, run this command in the MATLAB command line:

```
mex -setup
```

MATLAB should output this: 
**_MEX configured to use 'Microsoft Visual C++ 2022 (C)' for C language compilation_.**

## Build SITL Connector Library

- Unzip the _**"includes.zip"**_ file.
- Open the folder containing the Library in MATLAB.
- Add it to the MATLAB path and run **“make.m”** file to compile the _**"ardupilot_sil_connector.cpp"**_ file. If successful, _**"ardupilot_sil_connector"**_ MATAB Mex file will be created in the folder.

![image](https://github.com/user-attachments/assets/945159b0-6107-40d9-9eb6-daa66234d5a5)
