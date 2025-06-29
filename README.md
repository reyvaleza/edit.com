# edit.com
A rough linux terminal text editor that will mimic Microsoft's MS-DOS Edit

I am trying to learn C++ without having to instantiate classes to avoid using new and delete.\
\
Why? Because I am sick and tired of the way 'everyone' hype up Rust and put down C++ and others.\
\
So I thought I'm going to learn C++ by creating an edit.com-like terminal text editor for Linux. I just miss edit.com so much. Who knows, maybe other old farts like me out there are also missing the old DOS edit and wants it on Linux. That will make me a star in their eyes!\
\
So I started on this text editor since last month (May) and learning C++ slowly. But lo and behold, on mid-June, Microsoft announced the revival of the [MS-DOS Edit!](https://github.com/microsoft/edit) And made it work for Linux too! In Rust! Microsoft stole my thunder!!!\
\
Sucks. But here is the state of my learning. It doesn't even scroll yet, but at least the code is just over 1,000 lines. After adding scrolling, and maybe double-buffering, and maybe undo-redo, I hope it doesn't reach over 2,000 lines. The only class I did is the TextBuffer class, which I made as a singleton by way of a static instance so I don't have to instatiate.\
\
So here it is in its pure rough state, just to let you know where it is now. It's not very usable yet as it doesn't even open and save to a file yet. I'm still working on it so this is a work in progress.
