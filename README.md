# Python SDK/API library for Cisco MDS Switches.

This library will be useful for automating day to day tasks or developing new tools which involve Cisco MDS switches

* Python version: 3.6 and above
* Apache License, Version 2.0 (the "License")


## Installation Steps
1) First create a virtual environment with python3

       virtualenv testmdssdk -p python3

2) Activate the virtual env

       cd testmdssdk/
       source bin/activate
       
3) Next download the zip file from the github 

       wget https://github.com/Cisco-SAN/mdssdk/archive/master.zip
       
4) Unzip the file

       unzip master.zip 
           
5) Execute `source install.sh` 
       
       cd mdssdk-master/
       source install.sh
       
6) Once successfully done issue `pip list` and you should see mdssdk package installed
        
        >>> pip list
        Package    Version   
        ---------- ----------
        .
        . 
        mdssdk     1.0.1       <---
        .
        .
        
        
## Documentation

* http://mdssdk.readthedocs.io
