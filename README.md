# synapse-client

A wrapper application for easy installation of Synapse project
software applications (and their dependencies) via `pip`.

## Prerequisites

1. An installation of Python3 is required. Python 3.7 is the recommended version. 

    Installers for Windows and MacOS can be found here:
    * [Windows 64-bit](https://www.python.org/ftp/python/3.7.5/python-3.7.5-amd64.exe)
    * [MacOS-10.6 or greater (64/32bit)](https://www.python.org/ftp/python/3.7.5/python-3.7.5-macosx10.6.pkg) 
    * [MacOS-10.9 or greater (64bit)](https://www.python.org/ftp/python/3.7.5/python-3.7.5-macosx10.9.pkg) 


2. An installation of the `Git` source control management software is also 
required. The latest version is recommended. 

    Installers for Windows and MacOS can be found here:
    * [Windows](https://git-scm.com/download/win)
    * [MacOS](https://git-scm.com/download/mac)

## Usage

Installation can be performed using the `pip` command. For systems that 
have both Python2 and Python3 installed, use `pip3` instead.

```sh
pip3 install --upgrade --user git+https://github.com/informatics-isi-edu/synapse-client.git
```

##### Virtual environment installation

The software can be installed in a _virtual environment_ in order to keep it
isolated from other Python3 applications that may already be installed. 

1. Install `virtualenv`: 
    ```sh
    pip3 install virtualenv
    ```
2. Create a new virtual environment in (for example) `synapse-client`:
    ```
    virtualenv synapse-client
    ```
3. Activate the new virtual environment:
    * Windows:
        For a Windows command-prompt, use `activate.bat`, for Powershell, use `activate.ps1`:
        ```
        synapse-client\Scripts\activate.bat
        ```
    * MacOS:
        ```
        source synapse-client/bin/activate
        ```
4.  In the _activated_ virtual environment, install `synapse-client` via `pip3`:
    ```
    pip3 install --upgrade git+https://github.com/informatics-isi-edu/synapse-client.git
    ```

## Support
Issues can be reported via GitHub [here](https://github.com/informatics-isi-edu/synapse-client/issues). 

When reporting issues, please include OS type and version, Python version, and any output from 
the installation command or relevant error output when executing any of 
the installed tools. 