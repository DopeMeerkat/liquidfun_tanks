# Liquidfun Tanks
This uses the box2D physics engine with liquidfun to make a Tanks style game

The code for liquidfun can be found [here](https://github.com/google/liquidfun).

In order to run the code, make the following changes to the liquidfun source code and follow the build instructions found [here](http://google.github.io/liquidfun/Building/html/index.html).  
- replace `liquidfun/Box2D/Testbed/CMakeLists.txt` with `CMakeLists.txt`
- replace `liquidfun/Box2D/Testbed/Framework/Main.cpp` with `Main.cpp`
- replace `liquidfun/Box2D/Testbed/Tests/TestEntries.cpp` with `TestEntries.cpp`
- add `Tanks.h` to `liquidfun/Box2D/Testbed/Tests/`