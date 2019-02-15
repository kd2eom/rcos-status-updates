## Last Week's Accomplishments

Last week I worked on the Python script that calculates the ETA for a certain shuttle. I studied the code, figured out how it worked, and added comments to it (as it had practically no comments when it was originally written). I also thought of various alternate heuristics we can measure within this Python script to potentially make the ETA algorithm more accurate. Finally, my mentor and I noticed the program was taking a long time to run; after timing the program, I determined that the slowest part was downloading the shuttle data from the website (this takes a long time as the file is very large) and loading it into the program's memory. Thus, the slowdown is mainly caused by the large size of the file that must be downloaded. The actual algorithm which calculates the ETA based on the data completes in just a couple seconds, which is reasonable. I think that once we have this code running on the main server, it should be faster (since it won't have to download the data over an internet connection from the website).

## This Week's Plan

I will implement the different heuristics I thought of and tabulate my findings to see whether different heuristics yield significantly different results. I will report my findings to my mentor, who will then help us make a decision as of which heuristic we should use.

## Anything Blocking?

Nope.
