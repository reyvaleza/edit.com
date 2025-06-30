# edit.com
A barebones linux terminal text editor that will try to mimic Microsoft's MS-DOS Edit

I am trying to learn C++ without having to instantiate classes to avoid using new and delete.\
\
Because I'm sick and tired of the Rust hype, that's why. So I thought I'll learn C++ by creating an edit.com-like terminal text editor for Linux. I just miss edit.com so much. Who knows, maybe other old farts like me out there are also missing the old DOS edit and wants it on Linux. That will make me a star in their eyes!\
\
So I started on this text editor last month (May 2025) and learning modern C++ at the same time. But lo and behold, on mid-June, Microsoft announced the revival of the [MS-DOS Editor!](https://github.com/microsoft/edit) In Rust! And made it work for Linux too! Microsoft stole my thunder!!!\
\
Sucks. But here is my output so far. It doesn't even scroll yet, but at least the code is just over 1,000 lines for now. After adding scrolling, and maybe double-buffering, and maybe undo-redo, I hope it doesn't reach over 2,000 lines. I want to avoid classes but I have to create the TextBuffer and Screen classes, so I made them a Singletons by way of static methods so I don't have to instatiate and use pointers and new and delete, just reference variables. I always compile with a -std=c++23 switch.\
\
So here it is in its pure rough state. It's not very usable yet as it doesn't even open and save to a file yet. It is a work in progress -:).\
\
No, I'm not confident about my source code so you won't be seeing it any time soon. I don't want to be impaled and pilloried by the masters.
