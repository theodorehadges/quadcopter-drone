BEHOLD... THE TED-Copter5000
==========================

![dronepic](https://github.com/theodorehadges/quadcopter-drone/blob/master/images/selfiedrone.jpg "Drone selfie!")

I've always wanted to learn a little about electronics/robotics so this seemed like a fun and challenging place to start. In building this drone, I learned how to read circuit diagrams, solder, code hardware (e.g. interrupts), and more.

The Ted-Copter5000 is an Arduino-based 4-motor/propeller quadcopter controlled by a radio transmitter/receiver. It uses sensors (a breakoutboard with a gyroscope and accelerometer) to automatically orient itself to stay upright.

# Bill of Materials (general):
-frame with integrated PCB wiring
-accelerometer/gyroscope breakout board
-4 motors and ESCs
-4 sets of propellers
-battery and charger
-radio transmitter and receiver
-arduino UNO board
-standard electronics components (resistors, diodes, wire, LEDs, etc) 

![dronepic](https://github.com/theodorehadges/quadcopter-drone/blob/master/images/tabledrone.JPG "The drone!")

NOTE: I did not come up with this design myself. I heavily referenced [this](http://www.brokking.net) source for the first iteration of this build. 

### Modifications from original (to-do)
#### This is a to-do list of features I'd like to implement
* fine-tune the PROPORTIONAL/INTEGRAL/DERIVATIVE (PID) settings for better
  auto-leveling and stability
* add first-person view capability
  * mount a camera on the frame (using a gimbal for stability)
  * mount the camera receiver on the frame and try to use same battery as
    everything else
  * optional:  map a lever on the drone's controller
    (transmitter) so that the camera gimbal can be rotated by the person on
the ground with the controller
* home GPS location so that if it goes out of range, it returns to home
  automatically
* add voice-activated movements
  * start with "up" and "down", where "up" causes the drone to take flight
    and stall at, say, 5 meters up from its take-off position, and "down" causes the drone to land. If these two fundamental commands work, others will be easy  


