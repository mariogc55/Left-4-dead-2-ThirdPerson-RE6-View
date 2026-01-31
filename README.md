# Left-4-dead-2-ThirdPerson-RE6-View

## Installation:
- For Left 4 Dead 2 locate the route: .\common\Left 4 Dead 2\left4dead2\cfg
- If you have or not a file named autoexec.cfg, download and place the file named autoexec.cfg from this repository inside and replace the one you already had.
- In game, press the key "v" to switch between first person and third person perspective.
- You can change the bind keys as you like by editing the code in the autoexec.cfg file.

## The code inside the file is:
#### bind "v" "thirdpersonshoulder; togglezoom"
#### alias "defaultzoom" "zoom.90"

#### c_thirdpersonshoulderaimdist "720"
#### c_thirdpersonshoulderheight "0" 	//Y Axis
#### c_thirdpersonshoulderdist "45"		//Camera distance
#### c_thirdpersonshoulderoffset "20"	//X Axis
#### c_thirdpersonshouldersnapto "1"
#### c_maxdistance "200"
#### c_maxpitch "90"
#### c_maxyaw "0"
#### c_mindistance "30"
#### c_minpitch "0"
#### c_minyaw "-0"
#### cam_collision "1"	//Set to 0 to ignore camera collisions

#### togglezoom.off; c_thirdpersonshoulder 0;
#### defaultzoom;
