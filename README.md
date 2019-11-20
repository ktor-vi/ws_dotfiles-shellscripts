# Dotfiles and shell scripts workshop

## UNIX-like systems

Linux distros and MacOS are Unix-like (\*nix systems), they follow the basic principles formalised by the AT&T UNIX operating system.

With no doubt (and completely subjectively) \*nix OSes are the best, and i'll show *some* cool stuff about it
(CLI's, Dotfiles, Scripting, heck maybe even vim!)

## What is a dotfile and how to use them ?

Dotfiles, typically the .bashrc file are used to store configuration files about your IDE, Text editor, Terminal, etc

The problem is migrating these configs around several machines can be annoying and time-consuming, so i will show how to save them and retrieve them from *the internet*.

## What is a shell script ?
A shell script is a program designed to be run be a unix command-line interpreter (Your Terminal)

Your scripts will have to work accordingly to your Terminal --> 

```
#!/bin/bash
```

At the beginning of your .sh file
**Don't forget to set the script as executable :**

```
chmod +x yourscript.sh
```  

## Goal of the workshop : 

Save your configurations with a git bare repository and use shell scripts to fool around!
One of the good ways to start backing up dotfiles : 
[It's on me, don't say thanks](https://harfangk.github.io/2016/09/18/manage-dotfiles-with-a-git-bare-repository.html)
### Some more fun with shell scripts : 

1. Hello world
2. User input
3. Make directory
4. Send email
5. Some evil stuff you can think of

## ... You decide about the rest
