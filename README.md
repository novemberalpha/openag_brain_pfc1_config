# openag_brain_pfc1_config

Test Sensor

`rostopic echo /sensors/dht22_1/air_humidity/raw`

`rostopic echo /environments/environment_1/air_humidity/measured`


Test Actuation

`rostopic pub /actuators/grow_lights_1/cmd std_msgs/Bool True -1`

`rostopic pub /actuators/chamber_fan_1/cmd std_msgs/Bool True -1`
