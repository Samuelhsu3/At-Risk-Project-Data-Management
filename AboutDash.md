###Link to the current dashboard: 
https://atriskdata.onrender.com/
	-Note that it spins down with inactivity so it may take some time to load 

###Logging in
- When directed, you will be asked to provide a username and password pair
		-You may use the same ID as in your baycrest email (e.g my email is shsu@research.baycrest.org, so my username would be shsu)
-You may also use “At-risk”  as the username 
-All the passwords are currently set as “at-risk2022jmr”  (same as TONI log in)

###Using the dashboard
	-The Find tab allows you to view information about files, directories, and participants.
-The search function at the top allows you to search for specific participants 
-There are two dropdown menus in the find tab. The first dropdown displays all the participants that are currently on file, the second dropdown displays all the file/directories that have been tracked.   
-You may narrow the items displayed in the dropdown by using the filters
		-Filters applied will update BOTH the ID as well as the Filename dropdown
		-Once selected, the following can be viewed (Demo info, Studies, Files)
		-Details about the files can be further explored by clicking on the file names which includes transfer history, date tested, size, file number, file type, location tested, timepoint, current pathway on compute canada, and any notes about the files (renaming history, incomplete blocks, errors…)
	-Other tabs link you to any old or new tracking sheets used to complete the summary sheet, it also records where all the data are backed up
	-The naming systems that have been used are also detailed in the other tabs

###Editing, Updating, and Uploading
	-The code is currently stored in my private github repository 
		-assets/css (design)
		-credentials.py (the username and password pairs)
		-csv_to_json_converter.py (can be run locally to convert excel sheets)
		-main.py (dashboard)
		-requirements.txt (packages)
	-I update the excel sheet biweekly, I would recommend doing it in bulk 
	-Click the sync button from the custom menu to generate a template for the CC tracker. You can then commit to the JSON sheet and then download it. 	
-The dashboard is currently hosted on Render and new commits would require redeployment, any other host would probably also work (~3 minutes)
