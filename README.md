# NetBeans Project for Experimenting with Small Sorting Networks

Current functionality includes an application to manually extend the first 32 comparators of Green's sorting network on 16 wires and monitor the effect on the number of unsorted binary outputs. Here is the view from NetBeans when the project is opened:

![Project view](/netbeans.png "Project view from NetBeans")

The user can append new comparisons using the mouse to select a pair of wires.  When the application runs, a frame appears depicting the first stage of Green's sorting network with room for appending new comparators. The data panel at the bottom displays a list of added comapators on the left and a list of all unsorted binary outputs on the right. The 151 binary unsorted strings that appear initially are those that are produced by the first stage of Green's network:

![Project view](/gui1.png "Extending Green's first stage")

The user can add a comparator by clicking the mouse on a pair of wires. A comparator can also be picked up with the mouse and dragged to a new location, or discared. For every change, the data panel displays a current view of the unsorted binary outputs produced by the composite network (Green's 32 with the user-selected comparators added).

![Project view](/gui2.png "Extending Green's first stage")

### Suggestions for Extra Features

### Suggestions for Code to Support Other Experiments


