Hi there 👋

A little about me and my projects:

I started programming in the summer 2023 and has since been working hard to make my own editor from scratch in C, trying to limit my use of libraries to only the basic OS APIs and a few C standard libraries or simple header only libraries. This not only eliminates any dependency hell but also gives me a chance to learn new things.

A little about my editor:

Project currently sits at around 10k LoC:\
⚡Currently made for Mac only since I made the OS abstraction layer myself, but it should be fairly easy to por later since the abstraction layer is only one file (unity build)\
⚡Can handle up to 100k LoC for text files with the M2 chip (single core) without any issues (around 2k~ "regular" pages)\
⚡Currently using 5~15% CPU during active use, but there is still lots of ways to bring that number eventually\
⚡Supports basic syntax highlighting, and text is fully rebuilt/retokenized with almost every user input (100k LoC no problem)\
⚡Has a partly working immediate mode GUI system, which I am also building from scratch (supports basic windows and tooltip like menus)\
⚡Hopefully I will be able to open source the project or parts of the project sometime in the future, so others can benefit from it

Currently I'm working on refining and testing the UI system, but some next steps for the editor will include:\
🌱Adding the ability for the user to add custom build config files\
🌱Adding clickable error messages when when the user builds their project\
🌱Implementing more advanced refactoring tools\
🔭And many more...

I will hopefully also soon be able to share videos of the current state of the editor.\
Feel free to reach out to me about any relevant questions or projects 💬📫

Nicklas
