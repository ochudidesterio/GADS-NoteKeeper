
# GADS-NoteKeeper

A basic android application to display a list of courses and notes related to each course.


## Prerequisites

- Android studio with emulator running on API level 29
- Fundamental knowlegde of recyclerviews, navigation drawers, linearLayoutManager and gridlayoutmanager.

# Project Flow

## RecyclerView with LinearLayoutManager

It displays the courses and notes on a linear Layout.

![Notes](https://github.com/ochudidesterio/GADS-NoteKeeper/blob/master/images/Home.png?raw=true)


## RecyclerView with GridLayoutManager


It displays the courses on a grid of two columns

![Notes](https://github.com/ochudidesterio/GADS-NoteKeeper/blob/master/images/Courses.png?raw=true)


## Navigation Drawer and Menu


Its attached to the left edge of the main activity and has two items on the menu, that is courses and notes


![Notes](https://github.com/ochudidesterio/GADS-NoteKeeper/blob/master/images/navigation.png?raw=true)


## Add Note


This activity functions to add a new note. its launched on Onclick of FAB 


![Notes](https://github.com/ochudidesterio/GADS-NoteKeeper/blob/master/images/addNote.png?raw=true)


## Edit Note


This activity is loaded via a recycler view item click listener and one can edit a note at that position


![Notes](https://github.com/ochudidesterio/GADS-NoteKeeper/blob/master/images/edit%20notes.png?raw=true)





