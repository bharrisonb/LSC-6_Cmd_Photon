# LSC-6_Cmd_Photon

Control a LewanSoul LSC-6 6 Channel Servo Controller via a Particle Photon

This program has been placed on GitHub to provide the user community with a working example on how to communicate with the LSC-6 over a serial interface. The manufacturers protocol specific was poorly written and contain error in their examples. The main thrust of this repositiory is to illustrate how to create a command structure and use Serial1.write to transmit the command request for successful receipt by the LSC-6. 

Starting with this reference application of inverse kenematics at https://www.circuitsathome.com/mcu/robotic-arm-inverse-kinematics-on-arduino/  , this Particle Photon .ico program (see platform info at : https://www.particle.io/products/hardware/photon-wifi-dev-kit ) interacts over the TX/RX serial interface with a LewanSoul LSC-6 Server Controller board ( see http://www.lewansoul.com/product/detail-147.html ). This controller is used with the LeArm 6DOF Robotic Arm ( http://www.lewansoul.com/product/detail-123.html ).

Connect the TX pin  of the Photon to the RX pin of the LSC-6, the RX pin of the Photon to the TX pin of the LSC-6, and connect GND from the Photon to GND of the LSC-6.

Feel free to add to this repository with any additions or improvements that may be applied.
