#########################################################################
#how to delete multiple directries and how to detect multiple directries#
######################################################################### 

step#1
input command (ls /etc/apt/sources.list.d/)
this will list out all the entries for example (google-chrome.list) and (google.list)

step#2
to check wheater these entries contain any duplicate directries enter the command 
(cat /etc/spt/sources.listd/<entry name>)

this command will show all the directries contained in the name specific entry

step#3
to remove the entry with duplicate files use the command
(sudo rm /etc/apt/sources.list.d/<entry name>)



