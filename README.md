# SplitScreener

Collection of apps for creating split screen designs for DaVinci Resolve Fusion based on a customizable grid pattern.

## How it works
SplitScreener generates a grid object based on a columns and rows customizable pattern and lets the user create
Screens by clicking and dragging on the graphical representation of the layout (or typing commands, when in the CLI version).

The standalone app then generates a text file with code that can be pasted into Fusion to create compositions. 
The comp script version works directly within Fusion, accessing its API and generating a comp dinamically as the user
clicks and drags on the interface.
