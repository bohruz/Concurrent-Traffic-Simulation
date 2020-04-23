# A Concurrent Traffic Simulation

![Traffic Simulator](data/traffic_simulation.gif)

<img src="https://github.com/bohruz/Concurrent-Traffic-Simulation/blob/master/data/traffic_simulation.gif"/>

In this project I developed a multi thread traffic simulator in which vehicles are moving along streets and crossing intersections. Each intersection is equipped with a traffic light, traffic lights are needed for road safety. In this project I built a suitable and thread-safe communication protocol between vehicles and intersections to complete the simulation. 

For this project I used Modern C++ with concurrency safe guards like:
* Mutexes
* Locks
* Message Queues

## Dependencies for Running Locally
* cmake >= 2.8
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* OpenCV >= 4.1
  * The OpenCV 4.1.0 source code can be found [here](https://github.com/opencv/opencv/tree/4.1.0)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./traffic_simulation`.

