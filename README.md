# SRM SDG Hackathon 2023 
# Team Edge Developer’s
# Heart Rate Prediction Using LSTM Model in One-API Platform

The oneAPI-samples repository contains samples for the [Intel® oneAPI Toolkits](https://www.intel.com/content/www/us/en/developer/tools/oneapi/toolkits.html).

The contents of the default branch in this repository are meant to be used with the most recent released version of the Intel® oneAPI Toolkits.

## Find oneAPI Samples

You can find samples by browsing the *[oneAPI Samples Catalog](https://oneapi-src.github.io/oneAPI-samples/)*. Using the catalog you can search on the sample titles or descriptions.

You can refine your browsing or searching through filtering on the following:

- Expertise (Getting Started, Tutorial, etc.)
- Programming language (C++, Python, or Fortran)
- Target device (CPU GPU, and FPGA)

## Get the oneAPI Samples

Clone the repository by entering the following command:

`git clone https://github.com/oneapi-src/oneAPI-samples.git`

Alternatively, you can download a zip file containing the primary branch in repository.

1. Click the **Code** button.
2. Select **Download ZIP** from the menu options.
3. After downloading the file, unzip the repository contents.

### Get Earlier Versions of the oneAPI Samples

If you need samples for an earlier version of any of the Intel® oneAPI Toolkits, then use a [tagged version](https://github.com/oneapi-src/oneAPI-samples/tags) of the repository that corresponds with the toolkit version.

Clone an earlier version of the repository using Git by entering a command similar to the following:

`git clone -b <tag> https://github.com/oneapi-src/oneAPI-samples.git`

where `<tag>` is the GitHub tag corresponding to the toolkit version number, like **2023.2.0**.

Alternatively, you can download a zip file containing a specific tagged version of the repository.

1. Select the appropriate tag.
2. Click the **Code** button.
3. Select **Download ZIP** from the menu options.
4. After downloading the file, unzip the repository contents.

## Getting Started with oneAPI Samples

The best oneAPI sample to start with depends on what you are trying to learn or types of problems you are trying to solve.

| If you want to learn about...                                                        | Start with...
|:---                                                                                  |:---
| the basics of writing, compiling, and building programs for CPUs, GPUs, or FPGAs     |[Simple Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/simple-add) or [Vector Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/vector-add) samples <br> (You can use these samples as starter projects by removing unwanted elements and adding your code and build requirements.)
| the basics of using artificial intelligence                                          | [Getting Started Samples for Intel® AI Analytics Toolkit (AI Kit)](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Getting-Started-Samples)
| the basics of image rendering workloads and ray tracing                              | [Getting Started Samples for Intel® oneAPI Rendering Toolkit (Render Kit)](https://github.com/oneapi-src/oneAPI-samples/tree/master/RenderingToolkit/GettingStarted)
| how to modify or create build files for SYCL-compliant projects                      | [Vector Add](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL/DenseLinearAlgebra/vector-add) sample

>**Note**: The README.md included with each sample provides build instructions for all supported operating system. For samples run in Jupyter Notebooks, you might need to install or configure additional frameworks or package managers if you do not already have them on your system.

### Using Integrated Development Environments (IDE)

If you prefer to use an Integrated Development Environment (IDE) with these samples, you can download [Visual Studio Code](https://code.visualstudio.com/download) for use on Windows*, Linux*, and macOS*.

## Repository Structure

The oneAPI-sample repository is organized by high-level categories.

- [AI-and-Analytics](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics)
  - [End-to-End-Workloads](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/End-to-end-Workloads)
  - [Features-and-Functionality](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Features-and-Functionality)
  - [Getting-Started-Samples](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Getting-Started-Samples)
  - [Jupyter](https://github.com/oneapi-src/oneAPI-samples/tree/master/AI-and-Analytics/Jupyter)
- [DirectProgramming](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming)
  - [C++](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++)
  - [C++SYCL](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL)
  - [C++SYCL_FPGA](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/C++SYCL_FPGA)
  - [Fortran](https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/Fortran)
- [Libraries](https://github.com/oneapi-src/oneAPI-samples/tree/master/Libraries)
- [Publications](https://github.com/oneapi-src/oneAPI-samples/tree/master/Publications)
- [RenderingToolkit](https://github.com/oneapi-src/oneAPI-samples/tree/master/RenderingToolkit)
- [Tools](https://github.com/oneapi-src/oneAPI-samples/tree/master/Tools/)


## Platform Validation

Samples in this release are validated on the following platforms. 

### Ubuntu 22.04	
Intel(R) Xeon(R) Platinum 8352Y CPU @ 2.20GHz  
Intel(R) OpenCL Graphics, Intel(R) Data Center GPU Max 1550 3.0, (pvc)  
Opencl driver:  Intel(R) FPGA Emulation Platform for OpenCL(TM), Intel(R) FPGA Emulation Device 1.2 [2023.16.6.0.22_223734]  
Level Zero driver: Intel(R) Level-Zero, Intel(R) Data Center GPU Max 1550 1.3 [1.3.26241]  
oneAPI package version:  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49397  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49440   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49367 

12th Gen Intel(R) Core(TM) i9-12900  
Intel(R) UHD Graphics 770  3.0 ; (gen12, AlderLake-S GT1 [8086:4680])  
Opencl driver:  Intel(R) FPGA Emulation Platform for OpenCL(TM), Intel(R) FPGA Emulation Device 1.2 [2023.16.6.0.22_223734]  
Level Zero driver: Intel(R) Level-Zero, Intel(R) UHD Graphics 750 1.3 [1.3.26241]  
oneAPI package version:  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49397  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49440   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49367 

11th Gen Intel(R) Core(TM) i7-11700  
Intel(R) UHD Graphics 750 3.0, (gen12, RocketLake)   
Opencl driver:  Intel(R) FPGA Emulation Platform for OpenCL(TM), Intel(R) FPGA Emulation Device 1.2 [2023.16.6.0.22_223734]   
Level Zero driver: Intel(R) Level-Zero, Intel(R) UHD Graphics 750 1.3 [1.3.26241]   
oneAPI package version:  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49397  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49440   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49367 

### Windows 11
12th Gen Intel(R) Core(TM) i9-12900 	 
Intel(R) UHD Graphics 770  3.0 ; (gen12, AlderLake-S GT1 [8086:4680])  
Opencl driver:  Intel(R) FPGA Emulation Platform for OpenCL(TM), Intel(R) FPGA Emulation Device 1.2 [2023.16.6.0.28_042959]  
Level Zero driver: Intel(R) Level-Zero, Intel(R) UHD Graphics 750 1.3 [1.3.26561]  
oneAPI package version:  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49396  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49441   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49368 

11th Gen Intel(R) Core(TM) i7-11700  
Intel(R) UHD Graphics 750 3.0, (gen12, RocketLake)  
Opencl driver:  Intel(R) FPGA Emulation Platform for OpenCL(TM), Intel(R) FPGA Emulation Device 1.2 [2023.16.6.0.28_042959]  
Level Zero driver: Intel(R) Level-Zero, Intel(R) UHD Graphics 750 1.3 [1.3.26370]  
oneAPI package version:  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49396  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49441   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49368 

### macOS
Intel(R) Core(TM) i5-8500B CPU @ 3.00GHz  
    - Intel oneAPI Base Toolkit Build Version: 2023.2.0.49370  
    - Intel oneAPI HPC Toolkit Build Version: 2023.2.0.49443   
    - Intel oneAPI Rendering Toolkit Build Version: 2023.2.0.49398 

## Known Issues and Limitations

### Windows

- If you are using Microsoft Visual Studio* 2019, you must use Microsoft Visual Studio 2019 version 16.4.0 or newer.
- Windows support for the FPGA code samples is limited to the **FPGA emulator** and **optimization reports**. Only Linux supports **FPGA hardware** compilation. See any FPGA code sample README.md for more details.
- If you encounter `Error MSB6003 The specified task executable ... could not be run...` when building a sample program, it might be due to the length of the directory path. Move the `build` directory to a location with a shorter path. Build the sample in the new location.

## Intel ONEAPI Sign in 
### Step-1
click Create a Account
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/fbc31fa6-39d9-404f-8c2a-14d2151b9045)

### Step-2
Fill those Details
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/aa675440-9127-44c7-bb96-e34172966810)

### Step-3
Choose Standard Plan
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/990c5608-c08d-4877-bb5d-4a5e513f3961)

### Step-4
go to Training 
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/ec0c9273-9c96-4ded-a381-1c61d8b5e41c)

### Step-5
Click Machine Learning Using One-API
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/16da2adc-cce6-40b2-9712-7d6ba03a7d76)

Click Launch Button
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/a8411e91-81ee-42d9-8592-0a78256efe4a)

### Step-6
Open Shell
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/8a25c53f-039f-4839-80a6-d531dc830e28)

## Installing Required Library in one-API 
### Pandas
```bash
%pip install pandas
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/c88492f7-b187-422e-bfaa-8ac82f71d33e)

### Matplotlib
```bash
%pip install matplotlib
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/62331d2e-faa9-42b3-ac27-12a73c35f99b)

### Tensorflow
```bash
%pip install tensorflow
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/b962f02e-9ded-4a1a-9dcf-bf2be1c277bc)

### Numpy
```bash
%pip install numpy
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/28b299bd-33cd-4f7c-bfd4-c471bd1781c9)

### Scikit-learn Intelex
```bash
%pip install scikit-learn-intelex
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/2d66a362-121d-4814-a78c-811285cf881a)

### Scikit-learn
```bash
%pip install scikit-learn
```
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/7602e015-9728-496b-b601-02ccbdebfe0a)

## MAE & MSE Value without one-API
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/337e564f-5a84-44f3-876c-bd8c0b037ae6)
## MAE & MSE Value with one-API
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/2ac142c0-7cec-4eef-be74-7b94dbd79aab)
## Performance Graph
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/c0b0a01a-9730-4cab-9cff-12ad9d8d5c93)
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/afd0b61a-ffee-4ea5-a835-b332d7052386)
## Result
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/a30d165c-a087-4f83-be5d-d2e1eb3b2739)
## Benchmark:
![image](https://github.com/mughesh03/SRM-SDG-Hackathon-2023/assets/121656366/5e81275c-3211-47f6-911d-5f6499351641)

## Licenses

Code samples are licensed under the MIT license. See [License. txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/License.txt) for details.

Third-party program licenses can be found here: [third-party-programs. txt](https://github.com/oneapi-src/oneAPI-samples/blob/master/third-party-programs.txt).

## Notices and Disclaimers

© Intel Corporation. Intel, the Intel logo, and other Intel marks are trademarks of Intel Corporation or its subsidiaries. Other names and brands may be claimed as the property of others.


