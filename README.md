sexy-docs
=========

Make docs sexy with dexy.

Dexy helps your code to speak for itself. Show off your code with beautiful syntax highlighting. Write examples and Dexy will run them, inserting the output into any document you wish. Everything is based on live code, so updating is easy, syntax errors blow up on you, not your users, and typos are a thing of the past. With Dexy's smart caching, your code is only executed when it needs updating, saving you time while keeping your documents robust.

## Requirements

Install dexy: 

pip install dexy

or follow alternative options at http://www.dexy.it/install/

To check if Dexy is installed:

dexy version

## How it works

The first time you run dexy you will need to call dexy setup first so it can create some directories it needs (this is a safety measure so you don't run Dexy in the wrong directory): 

dexy setup
dexy

Dexy puts some of the finished documents into the output/ directory (the ones it thinks you are most interested in) and all the finished documents into the output-long/ directory (with uglier, but unique, filenames)