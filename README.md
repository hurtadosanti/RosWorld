# Ros World
Gazebo world for Udacity Robotics Software Engineer

## Setup
- Create build folder and open

        cd RosWorld && mkdir build && cd build

- Run cmake and make

        cmake .. && make

- Export variable for plugin

        export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:$PWD

## Run
- Run world

        gazebo world/Apparment.world

## License
MIT License Copyright (c) 2020 Santiago Hurtado