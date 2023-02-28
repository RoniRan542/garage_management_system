# garage_management_system:
management system designed and implemented in OOP with backup system.

## JsonCpp:
I used the jsonCpp library for managing the backup json files. 
In order to run these files you must install the jsonCpp lib: 
sudo apt-get install libjsoncpp-dev

## Makefile
no makefile is currently provided (future plans), so in order to compile these files and get the .out file, execute this line in linux terminal:
g++ test_garage.cpp garage.cpp garage_system.cpp user.cpp vehicle.cpp -ljsoncpp
