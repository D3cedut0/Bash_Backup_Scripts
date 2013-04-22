Bash_Backup_Scripts
===================

*************************************************************************
"Simple Backup" scripts collection 
*************************************************************************
Authors: Sebastiano Berardo , Andrea Beltrame  
2013 University of Verone 
*************************************************************************
* 1_Open terminal and go to your scripts directory (`cd" command);	
* 2_type `bash backup" to run scripts menù;				
									
 About
 	init-repo : make repo and backup folders			
  commit    : copy repo content to backup				
 	remove    : removes a file from repo and/or backup		
 	revert    : restores repo by using backup			
 	status    : displays differences between repo and backup	
 	file_search : displays files that contain specified pattern	
									
 Features:								
 -Work correctly if file or folder name contains space character	
 									
 -You can select script to run by typing its number or its name	
									
  ex. `1 test\ one" or `init-repo test\ one" make "test one" directory 
	and ".test one.bck" backup directory;				
									
 -Newest files are compared with older only using `diff" command	
									
 See scripts comments fore more information.				
	 								
 Installation: Type on terminal `sudo mv SCRIPTS_NAME /root/bin/"	
		run with simply typing `backup" on terminal.		
		Don't overwrite any file if already existing		
*************************************************************************
		sebastiano.berardo'at'studenti.univr.it			
		 andrea.beltrame'at'studenti.univr.it			
*************************************************************************
*************************************************************************
