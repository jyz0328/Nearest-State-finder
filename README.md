# Nearest-State-finder
Designed this project in Boston University in Sep 2023-Dec2023
1. Designed and implemented a C++ application,  which takes the latitude and longitude as input and returns the nearest state for this location information as result.
2. Employed KD tree for state’s location information storage and retrieval; applied majority voting algorithm on calculating the nearest state from the given input location.

# Nearest-state-country-finder
EC504 class project Nearest state/country finder

## Getting Started
```
git clone
cd Nearest-state-country-finder
```
Run `make` to complie the code</br>
Run `make run` will test the sample input for the code</br>
or `./load xxxx.txt`</br>
source code is under src</br>
## Input and output
Input txt to tesing the code is under input folder</br>
stracture of input file should be:
```
latitude
longitude
k
```
All output will show in consle and write in txt file under output folder</br>
## Features
#### Load Reference Points
loads reference points (including latitude, longitude, state, and county information) </br>
into the KD-tree from a file or other source.</br>

#### Query the nearest K reference points
Allow the user to enter a coordinate (latitude and longitude) </br>
and return the nearest K reference points, where K is a number between 1 and 10.</br>

#### Majority Vote for States and Counties
For a given reference point, determine the state </br>
and county by calculating the majority vote for the 5 nearest points.</br>
### `g++ -std=c++17 -o load load.cpp`</br>
this project code requirte c++ version 17</br>
