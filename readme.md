## Todo App
This is a basic todo app built in my programming lanuage Novus (https://github.com/mjdaws0n/novus), using my package manager Nox (https://github.com/mjdaws0n/nox

I also made it to try to learn Vim better, so it's written using Vim.

## Usage
Run this and it will tell you all you need to know.
```bash
$ todo help
Novus Todo App version: 1.0
Written in Novus

Usage:
todo help
todo list
todo add "<Task name>"
todo check <Task ID>
todo check -n "<Task name>"
$ 
```

## Build
```bash
nox init
novus main.nox
```

## Run
```bash
./build/YOU_SYSTEM/todo
```

## Install
For linux you can install it with the following command after building
```bash
sudo cp build/linux_x86_64/todo /usr/local/bin/todo
```

## Errors
I don't make mistakes so they error is most likley you're fault...
If there is something that breaks, delete this file to reset all you're tasks and you should be set `/home/YOUUSERNAME/.local/share/novus-tasks.txt`.

## Disclamer
Novus is under very early development, this code works on my OS, however it may not work on Windows, MacOS, or other CPU types, because I cannot be bothered to test.
