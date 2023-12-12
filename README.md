This is a PCB layout that is used to track real time data through telemetry for an electric vehicle.
There are certain limitations placed because of available components and resources provided by
the university. As for design choices, I have created groupings of components with shorter wires,
and limited pathings to limit shorts, as this board can be used for years to come. This also uses
a microcontroller programmed using STM32CubeIDE, which sends signal for which ports are compatible
with USB inputs and outputs that make it more usable by the autonomous team.

**After implementation, this board provides numerous benefits**	
	- There is now a bridge between the car's live outputs and readings for accel, velo, and more
 	  in real time.
	- Autonomous team now does not require taking load on their processing devices to track encoder
 	  data which can sometimes have lackluster update times.
 	- This board is planned to be compatible with next generation cars developed by the club, and does
  	  not require to be redesigned or updated for at least two more years.

This implementation is being put into use now, and can be used by anyone who requires it! Let me know if
you have any questions or concerns, or even suggestions for anything that can be done better for 
future PCBs!
