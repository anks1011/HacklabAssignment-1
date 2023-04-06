# HacklabAssignment-1

Task 1 Design a State Machine
Design a demo website which uses an FSM to control a traffic light as described below. The traffic light can be simulated with 3 buttons 
(Red, Green, and Yellow). The buttons turn black when inactive. 

Transitions:
Initial State is Red
If we're in state Green and wait for 15 seconds (6 minutes), then we can go to state Yellow.
If we're in state Yellow and wait 5 seconds, then we can go to state Red.
If we're in state Red and wait 20 seconds, then we can go to state Green. 


Task 1.1 Add a click event
Whenever the button is clicked, the state machine will jump to the corresponding state.
For example, if the current state of the traffic light is yellow and you press the green button, 
the traffic light will now continue from the green state (the red state will be skipped for this current iteration) 
