# FrequentlyUsedDnfCommands
These are some of my frequently used Fedora package management commands.

## List all repository

    dnf repolist

## List all packages in a repository

    sudo dnf repository-packages repo-name list

## List all packages installed from a repository

    sudo dnf repo-pkgs repo-name list installed

## DNF history commands

    sudo dnf history
    sudo dnf history info #
    sudo dnf history undo last
    sudo dnf history redo #
	
## Import signing key

    sudo rpm --import package-signing-key.pub

## Downgreade a pacakge

    sudo dnf --allowerasing downgrade package-name

## How to terminate a frozen ssh connection.

	$ Enter
	$ ~
	$ .
	
[Properly close a frozen SSH session](https://infertux.com/posts/2012/12/20/properly-close-a-frozen-ssh-session/)
