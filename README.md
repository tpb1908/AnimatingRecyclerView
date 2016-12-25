# Animating RecyclerView

A RecyclerView with animations when views enter

Each animation is timed such that the further a ViewHolder is from position 0, the longer the 
time until it enters.

Animation types-

Alpha- An alpha fade 

Horizontal- ViewHolders enter from offscreen, moving horizontally

Vertical- ViewHolders move vertically as they enter

**Warning** Vertical animation will not work with non equal ViewHolder heights


## TODO

~~Add an option for the direction of horizontal animation~~

Add an option to enter all views at the same time

Add an expand animation (Horizontal/Vertical)

Add an option to change the timescale

Add an option to change the direction of animation traversal
