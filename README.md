# manta_ros
This repository is meant to collect and keep track of the different repositories that exist for Manta.

## Downloading

1. Clone the repository
	```bash
	$ git clone git@github.com:vortexntnu/manta_ros.git
	```

2. Initialize the submodules
    ```bash
	$ cd ~/manta_ws/src/manta_ros/
	```
	```bash
	$ git submodule update --init --recursive
	```

After cloning this repository, navigate into manta_ros and run the command "git submodule update --init"

## Important when building

If you do not have cuda remember to add touch CATKIN\_IGNORE in darknet\_ros.
1. Navigate to home
	```bash
	$ cd
	```

2. Add CATKIN_IGNORE
	```bash
	$ touch manta_ws/src/manta_ros/darknet_ros/CATKIN_IGNORE
	```
