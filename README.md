# DibMap
DibMap is a network analyzer tool which scans TCP and UDP ports, determining their current status.

## Requirements
Minimum: Java 8.0.1 or later.  
Recommended: Java 15.0.1 or later.  

## Installation
To be able to install DibMap, you first need to clone the repository using the command 'git clone https://github.com/FrancescoCapu/DibMap'.  
Then, you have to compile the program using the command 'javac dibmap/*.java'.

## Syntax
Linux/macOS: [sudo] java dibmap.Main *target* [-t] [-u] [-p port[-port]]  
Windows: java dibmap.Main *target* [-t] [-u] [-p port[-port]]  
  
Run it either as normal user or administartor, depending on scan type.
