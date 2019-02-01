# gap_jumper
You want to directly cross from one spiral arm of the galaxy to another but there is this giant gap between them? This program helps you to find a way.

## Problem:  
You are an explorer in Elite: Dangerous und you are out there in the endless void. In a region with a really low star density. And you seem not to be able to find a way out of there (or to the other side) and you have just some few materials left to boost your jumps?

## Solution:  
Well, most likely you are treading on the path's of the ancients. Use their knowledge to your advantage. It is all available on the number one place to go for all exploration related information: EDSM. 
They have nigthly dumps of their database which contains information of all the star systems the community has discovered so far.

## What you'll get
This python 3 program uses these databases (which one is described in the source-code) to find stars to jump to between the system you are in (or near) right now and the system you want to jump to.
The program is NOT designed to find the shortest path, but the most economic path, needing the fewest boosted jumps possible.
Just put the necessary information (start- and end-coordinates, your jump-ranges and a bit more) at the beginning of the < gap_jumper.py > file and then call the same on the command-line.

## ATTENTION
The search in the database is inefficient and will take some time. But the void is patient.

Also, please read the comments especially in < gap_jumper.py > for additional information on how to use this program.
I may or may not provide a gui at a later time.
