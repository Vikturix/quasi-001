# About

This is a repository made to test out concepts such as finite state machines with the Quasimodo NXT robot, written in NXC (based on C). What you need to know is that it can walk and it can see distance.  

This will probably not be expanded upon very much, as the Quasimodo has limited capabilities, e.g. it can't turn, or carry much weight.  

FSM is the main project, and quasiB-001 is a basic walk cycle that operates on distance to obstacles. Debug will be for testing random concepts.

## Quasimodo walk

https://user-images.githubusercontent.com/183669/161541743-a992264b-3e47-4db5-a570-17352374020f.mP4

This implements a basic finite state machine.
1. State-1 be still 
    * button released
3. State 2 walk forward look for obstacles
   * button pressed 
   * sensor distance > 15
4. State-3 step back
   * button pressed
   * sensor distance <= 15

> In version 0.1 this results in a sort of a tedious dance if the obstacle remains there :) 

States distance and button state are displayed on screen.



