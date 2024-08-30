Hi there 👋

A little about me and my projects:

I started concentrating fully on programming in the summer 2023 and has since been working hard to make my own editor from scratch in C, seeking to limit my use of libraries to only the basic OS APIs and simple header only libraries. This not only eliminates over-complicated builds and dependency hell but also gives me a chance to learn new things, so it's a win-win.

A little about my editor:

⚡Project currently sits at around 10K lines of code and still runs single threaded\
⚡Currently MAC-only as I made the platform (abstraction) layer myself, but it should be fairly easy to port later since the platform layer is only one file, and I am only using limited functionality from the OS\
⚡Can handle up to 100K lines of code for text files with the M2 chip (single core) without any issues (around 2K~ "regular" pages)\
⚡Supports basic syntax highlighting, and text line buffers are fully rebuilt/retokenized with with every text edit (works fine even at 100K lines of code)\
⚡Has a partly working immediate mode GUI system, which I am also building completely from scratch\
⚡Simple file search functionality\
⚡Safe atomic writing to disk to secure data integrity\
⚡Simple config file loading, so the user can provide their own build system etc, keeping things simple (xcode clang only at the moment)\
⚡Hopefully I will be able to open source the project or parts of the project sometime in the future, so others can benefit from it, but this will require more work on the API

Currently I'm working on refining and testing the UI system, but some next steps for the editor will include:\
🌱Adding clickable error messages when when the user builds their project (almost done)\
🌱Implementing more advanced search and refactoring tools\
🌱Adding more sexy UI such as rounded rectangles and borders\
🔭And many more...

I will hopefully also soon be able to share more images or videos of the current state of the editor.\
Feel free to reach out to me about any relevant questions or projects 💬📫

Nicklas

<img width="994" alt="Screenshot 2024-08-30 at 10 41 48" src="https://github.com/user-attachments/assets/9590084c-0992-4795-87d2-4b5fc7631add">

