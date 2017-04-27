# openag_brain_pfc1_config

Import Fixtures

`openag db load_fixture ~/_path_/_to_/_file_/pfc1_default.json`


Test Sensor

`rostopic echo /sensors/dht22_1/air_humidity/raw`

`rostopic echo /environments/environment_1/air_humidity/measured`


Test Actuation

`rostopic pub /actuators/grow_lights_1/cmd std_msgs/Bool True -1`

`rostopic pub /actuators/chamber_fan_1/cmd std_msgs/Bool True -1`

Current ROS Topics

```pi@0466dacf13b3:~$ rostopic list
/actuators/air_flush_1/cmd
/actuators/chamber_fan_1/cmd
/actuators/grow_lights_1/cmd
/actuators/heater_core_1_1/cmd
/actuators/water_circulation_pump_1/cmd
/diagnostics
/environments/environment_1/air_carbon_dioxide/info
/environments/environment_1/air_carbon_dioxide/measured
/environments/environment_1/air_carbon_dioxide/raw
/environments/environment_1/air_flush_on/commanded
/environments/environment_1/air_flush_on/desired
/environments/environment_1/air_flush_on/measured
/environments/environment_1/air_flush_on/raw
/environments/environment_1/air_humidity/info
/environments/environment_1/air_humidity/measured
/environments/environment_1/air_humidity/raw
/environments/environment_1/air_temperature/commanded
/environments/environment_1/air_temperature/desired
/environments/environment_1/air_temperature/info
/environments/environment_1/air_temperature/measured
/environments/environment_1/air_temperature/raw
/environments/environment_1/light_illuminance/measured
/environments/environment_1/light_illuminance/raw
/environments/environment_1/light_intensity_blue/commanded
/environments/environment_1/light_intensity_blue/desired
/environments/environment_1/light_intensity_blue/measured
/environments/environment_1/light_intensity_blue/raw
/environments/environment_1/light_intensity_red/commanded
/environments/environment_1/light_intensity_red/desired
/environments/environment_1/light_intensity_red/measured
/environments/environment_1/light_intensity_red/raw
/environments/environment_1/light_intensity_white/commanded
/environments/environment_1/light_intensity_white/desired
/environments/environment_1/light_intensity_white/measured
/environments/environment_1/light_intensity_white/raw
/environments/environment_1/nutrient_flora_duo_a/commanded
/environments/environment_1/nutrient_flora_duo_a/desired
/environments/environment_1/nutrient_flora_duo_a/measured
/environments/environment_1/nutrient_flora_duo_a/raw
/environments/environment_1/nutrient_flora_duo_b/commanded
/environments/environment_1/nutrient_flora_duo_b/desired
/environments/environment_1/nutrient_flora_duo_b/measured
/environments/environment_1/nutrient_flora_duo_b/raw
/environments/environment_1/water_dissolved_oxygen/measured
/environments/environment_1/water_dissolved_oxygen/raw
/environments/environment_1/water_electrical_conductivity/measured
/environments/environment_1/water_electrical_conductivity/raw
/environments/environment_1/water_level_high/commanded
/environments/environment_1/water_level_high/measured
/environments/environment_1/water_level_high/raw
/environments/environment_1/water_oxidation_reduction_potential/measured
/environments/environment_1/water_oxidation_reduction_potential/raw
/environments/environment_1/water_potential_hydrogen/commanded
/environments/environment_1/water_potential_hydrogen/desired
/environments/environment_1/water_potential_hydrogen/measured
/environments/environment_1/water_potential_hydrogen/raw
/environments/environment_1/water_temperature/measured
/environments/environment_1/water_temperature/raw
/internal_diagnostics
/rosout
/rosout_agg
/sensors/dht22_1/air_humidity/info
/sensors/dht22_1/air_humidity/raw
/sensors/dht22_1/air_temperature/info
/sensors/dht22_1/air_temperature/raw
/sensors/gc0011_1/air_carbon_dioxide/info
/sensors/gc0011_1/air_carbon_dioxide/raw
```
