# adaptive-microphone
This design is a adaptive microphone. The system detects and tracks the primary source of sound in a room and adaptively fouces the microphone toward in the direction of the speaker.

The MCU in this system collects data (the timing that sensor detect the sound) from all sound sensors. Once it have the timing data ready, it has a serial of algorithms to process the timing data to location data (the angle to the microphone). And then, the MCU could output the location data to control the motor under the microphone.
