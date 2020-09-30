HOW TO RUN:

[remote pc] roscore
 
[quadruped pc] 'rosrun servo_move_keyboard servoMoveKeyboard.py' // then cancel ctrl-c

[quadruped pc] rosrun i2cpwm_board i2cpwm_board

[remote pc] roslaunch spot_micro_motion_cmd spot_micro_motion_cmd.launch

[remote pc] rosrun spot_micro_keyboard_command spotMicroKeyboardMove.py

TODO: see why the right side's knees are not the correct range/same as the left side

