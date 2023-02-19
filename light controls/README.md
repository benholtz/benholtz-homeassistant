Nest Camera Person Detection Lighting Control is a Home Assistant blueprint that allows you to turn on/off lights or scenes based on person detection from one or more Nest cameras or sensors. This blueprint also supports sunrise/sunset offsets, dynamic timeouts, multi-room control, and additional sensor types beyond Nest cameras and motion sensors, such as door sensors, temperature sensors, and humidity sensors. You can customize the behavior of the automation, including options for specifying the maximum luminosity level and the timeout multiplier.

Features:

- Turn on/off lights or scenes based on person detection from one or more Nest cameras or sensors
- Support for sunrise/sunset offsets, which allows you to adjust the automation based on the time of day
- Dynamic timeouts, which allows you to adjust the amount of time that the lights stay on based on the time of day and the level of activity in the room
- Multi-room control, which allows you to specify which lights are controlled by the automation
- Support for additional sensor types beyond Nest cameras and motion sensors, such as door sensors, temperature sensors, and humidity sensors
- Customizable behavior of the automation, including options for specifying the maximum luminosity level and the timeout multiplier

Instructions:

1. Create a new automation in Home Assistant and choose "From Blueprint".
2. Choose the "Nest Camera Person Detection Lighting Control" blueprint from the list of available blueprints.
3. Input a name for your automation.
4. Add a list of Nest cameras and sensors that you want to use for person detection.
5. Add a list of additional sensors beyond Nest cameras and motion sensors, such as door sensors, temperature sensors, and humidity sensors.
6. Specify the lights or scenes that you want to control with this automation.
7. Input a sunrise/sunset offset time.
8. Input multiple threshold values.
9. Input a timeout duration.
10. Specify which lights are controlled by the automation for multi-room control.
11. Customize the behavior of the automation by specifying the maximum luminosity level and the timeout multiplier.
12. Click "Save" to save your automation.

Advanced Usage:

This blueprint has hidden advanced logic that can be customized by advanced users. Advanced users can further customize the behavior of the automation by editing the blueprint's YAML code.

You can also use a switch or input_boolean entity to enable/disable this automation as needed. This is useful when you want to disable the automation temporarily, such as during a party or when you have guests over.

Additionally, you can use a script to override the automation and manually turn on/off the lights or scenes that are controlled by this automation. This is useful when you want to turn on/off the lights without triggering the automation, such as when you are watching a movie and don't want the lights to turn off automatically.