Hi there 👋

A little about me and my projects:

I started concentrating fully on programming in the summer 2023 and has since been working hard to make my own editor from scratch in C, seeking to limit my use of libraries to only the basic OS APIs and simple header only libraries. This not only eliminates over-complicated builds and dependency hell but also gives me a chance to learn new things, so it's a win-win.

A little about my editor:

⚡ Current size: 10K lines of code\
⚡ Platform: MAC (with later extensibility to other platforms)
⚡ Main features:\
    🌱 Core text edit engine (edit, undo/redo) with support of up to 100,000 lines\
    🌱 Basic syntax highlighting\
    🌱 OS layer for graphics, events, file I/O etc.\
    🌱 UI layer with auto layout engine (partly experimental)\
    🌱 Core app layer that goes to sleep and wait for events from the OS or other threads\
    🌱 Config files for custom build commands etc.\
    🌱 Simple build system to build a project, with error window to see compile errors\
    🌱 Simple single file search and replace system (will be extended hopefully soon)\
    🌱 General multithreading support with callbacks\
    🌱 App goes to sleep when inactive, wakes up by OS or thread events (event-driven)\ 
    🔭 And many more...\

Hopefully I will be able to open source the project or parts of the project sometime in the future, so others can benefit from it, but this will require more work on the API 🔭

I will hopefully also soon be able to share more images or videos of the current state of the editor.\

Nicklas

<img width="994" alt="Screenshot 2024-08-30 at 10 41 48" src="https://github.com/user-attachments/assets/9590084c-0992-4795-87d2-4b5fc7631add">

