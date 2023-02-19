## Nest Camera and Sensor Lighting Control

Turn on/off lights or scenes based on person detection from one or more Nest cameras or sensors. Support for sunrise/sunset offsets, dynamic timeouts, multi-room control, and additional sensor types beyond Nest cameras and motion sensors.

### User Instructions

1. Install and configure Nest cameras and sensors in Home Assistant.
2. Install this blueprint by going to "Blueprints" in the Home Assistant UI, clicking the three dots in the top right corner, and selecting "Import Blueprint".
3. In the "Import Blueprint" dialog, paste the YAML code for this blueprint and click "Preview Blueprint".
4. Configure the blueprint with the following inputs:
    - `Nest Cameras and Sensors`: A list of Nest cameras and sensors to be used for person detection.
    - `Additional Sensors`: A list of additional sensors beyond Nest cameras and motion sensors, such as door sensors, temperature sensors, and humidity sensors.
    - `Lights or Scenes`: A list of lights or scenes to control.
    - `Sunrise/Sunset Offset`: Time offset from sunrise or sunset to adjust automation.
    - `Thresholds`: A list of thresholds to trigger automation based on person detection activity.
5. Save the blueprint and create an automation from it.
6. Test the automation by simulating person detection using your Nest cameras and sensors.

### Features

- Turn on/off lights or scenes based on person detection from one or more Nest cameras or sensors.
- Support for sunrise/sunset offsets, which allows you to adjust the automation based on the time of day.
- Dynamic timeouts, which allows you to adjust the amount of time that the lights stay on based on the time of day and the level of activity in the room.
- Multi-room control, which allows you to specify which lights are controlled by the automation.
- Support for additional sensor types beyond Nest cameras and motion sensors, such as door sensors, temperature sensors, and humidity sensors.
- Customizable behavior of the automation, including options for specifying the maximum luminosity level and the timeout multiplier.
- Hidden advanced logic that can be customized by advanced users.