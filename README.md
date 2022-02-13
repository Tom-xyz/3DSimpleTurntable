# 3DSimpleTurntable
3D Model files and source code for rotating turntable. Raspberry Pi, DC servo and PWM modulator required.

## Preview
![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/preview.gif)


## Construction


### Printing
3D Model Files are available in the following directory: '3D Model'
* Print the base ('v0_stepper_rotator_base.obj')
* Print the motor fixture ('v0_stepper_rotator_lid.obj')
* Print the top/turntable (TODO)

![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/3d_print_1.jpg)
![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/3d_print_2.jpg)


### Assembly

TODO: Wiring Diagrams

TODO: Parts list


![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/internals.jpg)


![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/motor_lid.jpg)


![](https://github.com/Tom-xyz/3DSimpleTurntable/blob/main/Preview/wiring.jpg)



### Demo

Source code for the stepper motor servos is provided in the 'src' directory.

Upload the Python script to your Raspberry pi and invoke it:
`python3 StepperMotorDemo.py`