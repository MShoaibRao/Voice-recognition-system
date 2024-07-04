# Voice-recognition-system
Idenify the person by its voice

Step-1:SetUp
	python3 and pip should be installed if not installed. in ubuntu python is preinstalled.
 
	first install 2 python pkgs
 
	Pkgs:
		pveagle==1.0.1 
		pvrecorder==1.2.2
	
	Commands to Install:
		sudo pip3 install pveagledemo
		sudo pip install pveagle==1.0.1
		sudo pip install pvrecorder==1.2.2
		(if error in installing then specify the version)
	
			---------------------------------------------------------------------

Step-2:Enroll

	1.Enroll a Person Voice.
	2.Run the script by this cmd:
	eagle_demo_mic enroll --access_key {For Access contact: shoaib.tashrif@gmail.com} --output_profile_path "Output_filepath"
	
	3.Now Microphone is active and start speaking, when enrollment %age is 100%, voice is saved in bject file on given output filepath
	4.add more persons if u want.
	
			---------------------------------------------------------------------
			
	
Step-3:Testing

	1.Run the script by this cmd:
	eagle_demo_mic test --access_key {For Access contact: shoaib.tashrif@gmail.com} --input_profile_paths "file1" "file2"
	2.add more file name to compare.
	3.Remember file1 file2 .. are same as u previously saved object files.
	4.%age will be showned how match it matches from any voice.
	5. 1.00 means exact match.
	
	
	
	
	
	
