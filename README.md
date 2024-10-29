# HeyAbby OG DP Mappings

## Intro

Who knew Hey Abby is just tuya at core.

**Automation time baby.**

Using [LocalTuya](https://github.com/rospogrigio/localtuya), these and the basic tuya key grabbing, Abby can be added to home assistant. The rest will be mapped in time.

## Warning

Though the Abby's app stops working if you don't remove the box you can still use just about everything.

## Table

Remaining:  102, 108, 134

| **Parameter**        | **ID**              | **Description**                         |
| -------------------- | ------------------- | --------------------------------------- |
| switch               | 0 (switch)          | Lights                                  |
| bright_value         | 5 (number)          | Light Intensity                         |
| temp_current         | 6 (number)          | Environment Temp                        |
| humidity_current     | 7 (number)          | Environment Humidity                    |
| alarm                | # (binary_sensor)   | Boolean Report Only                                   |
| show_app_logo        | # (switch)          | Boolean Send+Report                                |
| Ventilation          | 103 (number)        | Exhaust Fan                             |
| water_temperature    | 104 (sensor)        | Water Temp                              |
| water_level          | 105 (sensor)        | Water Level                             |
| door                 | 106 (binary sensor) | Door                                    |
| height               | 107 (sensor)        | Plant Height (0.1 scale + cm [i think]) |
| Add_fertilizer       | 108 (switch)        | Fertilizer Door (Older OG models)       |
| human_detection      | 109 (binary sensor) | Human Present                           |
| o2                   | 110 (switch)        | Not Sure                                |
| up_water             | 111 (binary_sensor) | Low Water                               |
| weekcycle            | 112 (sensor)        | Growcycle Week                          |
| pump_water           | 113 (switch)        | Water Pump                              |
| replace_skin         | # (?)               | Enum Send+Report                                     |
| input_air_flow       | 115 (number)        | Intake Fan                              |
| turn_on_the_light    | 116 (number)        | Light On Time                           |
| turn_off_light       | 117 (number)        | Light Off Time                          |
| air_pump             | 118 (switch)        | Air Pump                                |
| child_lock           | 119 (switch)        | Child Lock                              |
| device_status        | 120 (sensor)        | Device Status                           |
| fan_in_fault         | # (binary_sensor)   | Intake Fan Issue                        |
| fan_out_fault        | # (binary_sensor)   | Exhaust Fan Issue                       |
| sensor_rh_fault      | # (_)               |                                         |
| sensor_water_fault   | # (_)               |                                         |
| sensor_level_fault   | # (_)               |                                         |
| water_pump_fault     | # (_)               |                                         |
| gas_pump_fault       | # (_)               |                                         |
| sensor_height_fault  | # (_)               |                                         |
| on5v                 | 101 (number)        |                                         |
| off5v                | 129 (number)        |                                         |
| pump_water_finished  | # (_)               |                                         |
| fan_enable           | 131 (Switch)        |                                         |
| light_all_onoff      | 133 (sensor)        | None                                    |
| timetofeedabby       | # (_)               |                                         |
| app_rewrite_sn       | 135 (Sensor)        | None                                    |
| speaker_on_off_mode  | 136 (Sensor)        | None                                    |
| job_to_do_show_pic   | # (_)               |                                         |
| new_job_show_picture | 137 (_)             | Screen                                  |
| celebrate_welcome    | 138 (switch)        | Screen                                  |
| time_stamp           | 140 (sensor)        | None                                    |
| silent_mode          | 141 (sensor)        | None                                    |
| auto_lock            | 142 (switch)        | Locks Door                              |
| dpid_test_mag2       | 143 (switch)        | None                                    |
| dpid_test_mag1       | 144 (switch)        | None                                    |
