# Gitmmit

Gitmmit is a simple tool where you can automatically commit new changes to your repository without having to open Github.
<br />
<br />
The tool is for simple commits only, handeling all types of changes to files (since it will run GIT on the specified folder, that needs to have a .git folder), making a simple commit message and having the capability of specifying a branch to commit to.

## Download
Download Gitmmit latest version [here.][download]

## Dependencies
- [.Net Framework 4.8 runtime][dotnet]
- [Git (windows)][gitw]
<br /> or
- [Git (macOs)][gitm]

## Commands list
This is the list of commands in case you want to use the app via CMD.

### Commands:
- -p : Path where your .git folde is located (required)
- -m : Commit message (not required)
- -b : Branch to commit. If none is specified, your default branch will be selected (not required)
- -w : Turns off the watermark on the commit message in case you make a custom message. The water mark is a "(via Gitmmit)" at the end (not required)

#### Example usage:
``gitmmit -p C:\Desktop\My website\ -m Index.html edited -b master -w``

## Environment variable
If you want have easy access to the tool in a way you don't need to reference the directory where the exe is, you can register a new environment variable to reference the exe path, so that next time you open the CMD, you can type directly the Gitmmit commands and it will work straight away!

### Registering:
Remember: do not have the CMD open while doing this, because the changes are only going to apply when you close it and open again.
<br />
- 1: On "My computer" right click it and go to Properties.
- 2: Find the option "Advanced system settings" and access it.
- 3: Go to "environment variables".
- 4: On "System variables", find "Path" and click "Edit" with it selected.
- 5: Click "New" and add the path where the Gitmmit.exe is. Make sure to put in a place where you won't move it, so you don't need to change the variable later.
- 6: Press "Ok" on everything and you are done!

[gitw]: https://gitforwindows.org
[gitm]: https://git-scm.com/download/mac
[dotnet]: https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer
[download]: https://github.com/theshoperr/Gitmmit/releases
