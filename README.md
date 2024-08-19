Hi there 👋

A little about me and my projects:

I started concentrating fully on programming in the summer 2023 and has since been working hard to make my own editor from scratch in C, seeking to limit my use of libraries to only basic OS APIs and or simple header only libraries. This not only eliminates over-complicated builds and dependency hell but also gives me a chance to learn new things, so it's a win-win.

A little about my editor:

Project currently sits at around 10k LoC:\
⚡Currently works for Mac only since I made the OS abstraction layer myself, but it should be fairly easy to port later since the abstraction layer is only one file (unity build)\
⚡Can handle up to 100k LoC for text files with the M2 chip (single core) without any issues (around 2k~ "regular" pages)\
⚡Currently using 5~15% CPU during active use, but there are still many ways to bring that number eventually\
⚡Supports basic syntax highlighting, and text is fully rebuilt/retokenized with almost every user input (even if at 100k LoC)\
⚡Has a partly working immediate mode GUI system, which I am also building from scratch (supports basic windows and popup menus)\
⚡Simple search functionality which can highlight text, utilizing the ui system\
⚡Safe atomic writing to disk to secure data integrity\
⚡Simple config file loading, so the user can provide their own build system etc, keeping things simple\
⚡Hopefully I will be able to open source the project or parts of the project sometime in the future, so others can benefit from it, but this will require more work on the API

Currently I'm working on refining and testing the UI system, but some next steps for the editor will include:\
🌱Adding clickable error messages when when the user builds their project\
🌱Implementing more advanced search and refactoring tools\
🔭And many more...

I will hopefully also soon be able to share more images or videos of the current state of the editor.\
Feel free to reach out to me about any relevant questions or projects 💬📫

<img width="700" alt="Screenshot 2024-08-19 at 07 40 57" src="https://github.com/user-attachments/assets/b0c005a7-5ea7-4b72-8b10-09c429a4644c">

Nicklas
