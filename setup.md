---
layout: page
title: Setup
root: .
---


## Ensure you have a working shell

"The shell" is what we call a program that enables us to send commands to the computer and receive output. It is also referred to as the terminal or command line. There are many different programs that can operate as a shell. We will use the `bash` shell (though if you are using a Mac, you may use a shell called `zsh`).

### The instructions below should get you a working shell running on your own laptop or desktop computer.

> ## Windows users
> Computers running the Microsoft Windows operating systems  do not automatically have a Unix Shell program installed. They have Powershell and the DOS shell instead. 
> 
> However, since the release of Windows 10, Microsoft has provided the [Windows Subsystem for
> Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10), abbreviated WSL, that allows a
> complete virtual Linux system hosted on your Windows desktop or laptop. You can actually install multiple Linux distributions at the same time, but I recommend
> sticking to the default (Ubuntu). To install WSL and the default Ubuntu distribution, take the following steps:
> 
> 1. find the PowerShell application and open it _in Administrator mode_ (right click on the application icon to run in Administrator mode)
> 2. From the PowerShell command line, type `wsl --install`. Wait for the command to finish, then type `wsl -l -v` to see what Linux distributions have been installed. The default at time of writing is Ubuntu 22.04 under WSL 2.
> 3. From the start menu, type "Linux", or "Ubuntu", and you should have a Linux distribution available to run. The first time you launch it might be a bit slow.
> 
>Additional references are below.
> #### Reference
> * [Git for Windows](https://git-for-windows.github.io/)
> * [Using the Windows 10 Bash Shell](https://www.howtogeek.com/265900/everything-you-can-do-with-windows-10s-new-bash-shell/)
{: .windows}


> ## Mac OS X users
> For Mac computer users, the default Unix Shell is either `bash`  or  `zsh` and it is available via the Terminal Utilities program within your Applications folder.
>
> To open Terminal, try one or both of the following:
> * Go to your Applications. Within Applications, open the Utilities folder. Locate Terminal in the Utilities folder and open it.
> * Use the Mac ‘Spotlight’ computer search function. Search for: `Terminal` and press <kbd>Return</kbd>.
>
> 
> 
> > ## Homebrew and iTerm2
> > 
> > - While the MacOSX system comes with a proper shell by default, you will need a package manager to get the most out of it. I recommend installing the Homebrew ([https://brew.sh](https://brew.sh)) package manager on MacOSX. This will help you manage software installation from the command line.
> > - While the default terminal application on MacOSX is pretty good, the [iTerm2](https://www.iterm2.com/) application is an excellent alternative to the standard MacOSX terminal.
> > 
> {: .idea}
> #### Reference 
> For more reading, go to[ How to Use Terminal on a Mac](http://www.macworld.co.uk/feature/mac-software/how-use-terminal-on-mac-3608274/)
{: .osx}

> ## Native Linux users
> The default Unix Shell for Linux operating systems is usually Bash.
> On most versions of Linux, it is accessible by running the [(Gnome) Terminal](https://help.gnome.org/users/gnome-terminal/stable/)
> or [(KDE) Konsole](https://konsole.kde.org/)
> or [xterm](https://en.wikipedia.org/wiki/Xterm),
> which can be found via the applications menu or the search bar.
> If your machine is set up to use something other than bash, you can run it by opening a terminal and typing `bash`.
>
{: .linux}


## Some files you will need

*After you have a working shell,* you need to download some files to follow this lesson:

1. Download [`data-shell.zip`]({{ page.root }}/data/data-shell.zip) and move the file to a location you can access in your bash environment. 
2. Unzip/extract the file . You should end up with a new folder called `data-shell`.
2 .Open a terminal and type `cd`, then press the Enter key. That last step will make sure you start with your home folder as your working directory.

In the lesson, you will find out how to access the data in this folder.

