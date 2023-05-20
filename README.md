# Organic

This is a thought-process oriented library that is currently being prototyped.  For the most part, it is okay to ignore this library within the Proliferation Project until it is built out to the Datendrache's liking.

# Purpose

One of the AI challenges is that the chain of thought is hard to manage.  In 2003, Datendrache was able to demonstrate a form of event driven artificial intelligence that could have "measurable creativity" in the manner used to solve a problem using a series of tools.

After reducing the data structure, he concluded the following was a viable strategy to capture "chain of thought":

A "CELL" that receives a set of data pertinent to the problem being "thought about"
An "ORGAN" which is a collection of cells.
An "ORGANISM" which is a collection of organs.

Each cell receives an event containing the pertinent data.
Each cell modified the data as it is instructed, no modifications equate to a state of no resolution and the "time to live" of the thought increments by once cell.
At the end of each cell's processing, if the cell's TTL exceeds the number of cells in the Organ.
If the cell modifies the data by contributing, the TTL is reset back to 0.

This way, the organ will continue to "think" about a problem until there is no additional value it can add.

I think this was an XPrize or something.
