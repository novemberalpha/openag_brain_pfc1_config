# openag_brain_pfc1_config

Import Fixtures

`openag db load_fixture ~/_path_/_to_/_file_/pfc1_default.json`


Test Sensor

`rostopic echo /sensors/dht22_1/air_humidity/raw`

`rostopic echo /environments/environment_1/air_humidity/measured`


Test Actuation

`rostopic pub /actuators/grow_lights_1/cmd std_msgs/Bool True -1`

`rostopic pub /actuators/chamber_fan_1/cmd std_msgs/Bool True -1`
