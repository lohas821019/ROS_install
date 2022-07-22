# ROS_install

[ROS_install tutorial](https://industrial-training-master.readthedocs.io/en/melodic/_source/setup/PC-Setup---ROS.html)


```
git clone -b melodic https://github.com/ros-industrial/industrial_training.git ~/industrial_training 
```

```
#ubuntu-18.04.6

cd ~/industrial_training/gh_pages/_downloads

bash ros-industrial-training-setup.sh

```

```
# install python pip
sudo apt install python-pip
sudo python -m pip install -U pip
sudo python -m pip install -U setuptools

```

[ROS Qt Creator Plug-in](https://ros-qtc-plugin.readthedocs.io/en/latest/_source/Improve-ROS-Qt-Creator-Plugin-Developers-ONLY.html)

```
git clone https://github.com/ros-industrial/ros_qtc_plugin.git -b devel

cd ~/ros_qtc_plugin

./setup.py

```


```
#Configuration Check

~/industrial_training/.check_training_config.bash
```
