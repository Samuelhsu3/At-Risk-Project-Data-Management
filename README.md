# Data-Management-Documentation

Not everything I have ever wrote are saved here but almost everything you will ever need should be here. The work flow of Data Collection -> Data Transfer -> Data Tracking -> Data Management are displayed in the folders above. While conducting data validation I realized that errors more often then one would expect and so tried my best in automating as much as I could using shell scripts. 

For code in the data collection and data transfer folder, I had chatgpt write the advanced and user friendly explanations. I am assuming that those are the scripts that might need to change in the future. I added the oversimplified explantions myself.

I also took the time to recover some of the more important scripts that were used for the data migration project and added them to [Saved Scripts](Saved_Scripts).
Some are still being used while others are only there as reference. 
Older versions that have been retired are in [Legacy Code](Legacy_Code).

There are 10 scripts inside [Data Collection](Data_Collection). (Sorting, transfer between hardware, session folder generation).
There are 10 scripts inside [Data Transfer](Data_Transfer). (SCP from client side to server) 
There are 8 scripts inside [Data Tracking](Data_Tracking).
(Log generation, sheet syncing, object handling)

There are 38 scripts that may be needed for processing to sourcedata format and they are stored in the  [Data Management Folder](Data_Management). These are divided by projects. 
The guide on using the [DashBoard](DashBoard_Guide.ipynb) and other information about the project can be found in the main folder. The guide on server mounting and ssh keys can also be found in the in the main folder.


You can save any of these scripts and test them out in your own scratch folder but remember to replace pathways if applicable. The [Documentation Notebook](Documentation.ipynb) summarizes everything pretty well and references most (but not all) of the scripts within its explanation. 

Feel free to add your own code and save them here.

  