# Data-Management-Documentation

Not everything I have ever wrote are saved here but almost everything you will ever need should be here. The work flow of Data Collection -> Data Transfer -> Data Tracking -> Data Management are displayed in the folders above. While conducting data validation I realized that errors more often then one would expect and so tried my best in automating as much as I could using shell scripts. 

For notebooks in the data collection and data transfer folders, I had chatgpt write the advanced and user friendly explanations to my code so they might sound a bit off. I am assuming that those are the scripts that might need tailoring in the future. The other markdowns I wrote myself.

I also took the time to recover some of the more important scripts that were used for the data migration project and added them to [Saved Scripts](Saved_Scripts).
Some are still being used while others are only there as reference. 
Older versions that have been retired are in [Legacy Code](Legacy_Code).

There are 10 scripts inside [Data Collection](Data_Collection). (Sorting, transfer between hardware, session folder generation).
There are 10 scripts inside [Data Transfer](Data_Transfer). (SCP from client side to server) 
There are 8 scripts inside [Data Tracking](Data_Tracking).
(Log generation, sheet syncing, object handling)

There are 38 scripts that may be needed for processing to sourcedata format and they are stored in the  [Data Management Folder](Data_Management). These are divided by projects. 
The guide on using my dashboard and other information you might need for the project can be found in the [Guides](Guides) folder.

You can save any of these scripts and test them out in your own scratch folder but remember to replace pathways if applicable. The [Documentation Notebook](Documentation.ipynb) summarizes everything pretty well and references maybe a third of the scripts within its explanation? I dont' really

Good Luck!

-Samuel Hsu 