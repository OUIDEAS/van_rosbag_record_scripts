# van_rosbag_record_scripts

Convinient location to store the rosbag record scripts. 

Rosbags will be recorded to script file location, so run the script where you want the rosbag to begin.

All available van topics are in the rosbag_record_all_no_theora_compressed.sh file.

Theora and compressed topics utilize a compression algorithm that significatnly lowers the output frequency of the recorded image streams to ~ 3 fps. For this reason, use of these scripts is greatly encouraged over simply using ```rosbag record -a```. 