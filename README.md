# Rebar-Numbering
Script for manulally controlling the rebar numbering in Revit, rather than using the random numbering system and losing previous numbers.

Based on Einar Raknes work found in the link below, I jsut took the ordering out of it so you could use whatever numbers you wanted.
https://forum.dynamobim.com/t/renumber-rebar-numbers-with-dynamo/6360

---

# How To

1)	Download the files, open the Dyanmo Player and open the folder
2)	Click play on the “Rebar Numbering Setup”. This will create a new schedule called “Rebar Numbering Control” where the schedule numbers can be changed. It will also set all the Schedule numbers equal to the rebar number. If you get any errors here just click the input button and check the schedule type is set to “RegularSchedule”
3)	Sort/group your new schedule. I couldn’t automate this bit easily, it will take some time to figure out, so go into the schedule and sort/group with the below settings (make sure Itemize every instance is turned off):



4)	Make whatever number changes you want in the schedule numbers and then click play on the “Rebar Numbering” script. Any problems just check the input is set to “Structural Rebar”. If you accidentally use a duplicate number you will get an error message and the numbering will go … odd! Just correct the number and press play again.
