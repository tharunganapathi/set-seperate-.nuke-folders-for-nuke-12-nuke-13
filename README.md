The reason why I have created the seperate folders for nuke 12 and nuke 13 is, 
nuke 12 supports python 2, and nuke 13 supports python 3


1. create nuke12 & nuke13 folders in .nuke directory
2. copy the correspondig files, scripts and gizmos in respective folders. 
3. create init.py in .nuke directory
      This will redirect the nuke to look for the respective path, before it gets launched
4. Also create recentfiles.py
      Because by default, nuke will create "recentfiles" file in .nuke directory
      so we have to copy the "recentfile" file to nuke 12 & nuke 13 folders




https://www.youtube.com/watch?v=mADEtHwTTSA&ab_channel=THARUNGANAPATHI
In this above link, I have explained how to set seperate .nuke folders for nuke 12 and nuke 13.



