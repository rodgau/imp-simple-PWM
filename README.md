## Welcome to imp-simple-motor ##


This is an introductory [electric imp](http://electricimp.com) project to set a PWM output according to a potentiometer's reading.
# Overview #

Nothing fancy here. You can use this to control the speed of a DC motor or the brightness of an LED, for example. Set your potentiometer knob to any position and the motor's speed will match, varying from rest/zero to max output (motor hooked up to your electric imp via an h-bridge).

### Device-side Functionality  ###
- pot read 100x/second
- PWM duty cycle updated accordingly from 0-100%
- 1x/second, results are sent to server.log
- 20x/second, results are streamed out serial port for monitoring inside your terminal app
- each function runs in seperate timer loop
### Agent-side Functionality  ###
None.
