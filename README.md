# REEF Adaptive Controller Bundle
Contains all the packages needed to run the REEF [Adaptive Controller](https://github.com/uf-reef-avl/reef_adaptive_control). Please refer to the repo for documentation.

## Installation
```asm
mkdir -p adaptive_ws/src
cd adaptive_ws/src
catkin_init_workspace
git clone https://github.com/uf-reef-avl/reef_adaptive_control_bundle
cd reef_adaptive_control_bundle
git submodule update --init --recursive
cd ../..
catkin build
source devel/setup.bash
```