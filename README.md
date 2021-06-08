# Demonstration of Child Process in nodejs

This is a simple repo, to explain - how to use **child-process** in Nodejs.

Each of the methods i.e. `exec execFile spawn & fork` is explained in this repo - with their respective file names.

- **exec** - `exec_demo.js`
- **execFile** - `exec_file_demo.js` (also uses `somefile.sh`)
- **spawn** - `spawn_demo.js`
- **fork** - `fork_demo.js` (also uses `longtask.js`)

## Note (for windows user)

You should use (or modify) the commands that are compatible with your operating system. for example: in **exec_demo.js** we used `ls -lh`, the windows compatible would be `dir` commmand, so you need to change that accordingly.

## Tutorial (YouTube)

You can also watch the video related to the explanation on youtube:

[exec, execFile, spawn] (https://www.youtube.com/watch?v=bbmFvCbVDqo)

[fork] (https://www.youtube.com/watch?v=7cFNTD73N88&t=11s)

## Author

[Truly Mittal] (https://trulymittal.com)
