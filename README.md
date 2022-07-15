# Gitmmit

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

#### Example usage: gitmmit -p C:\Desktop\My website\ -m Index.html edited -b master -w



[gitw]: https://gitforwindows.org
[gitm]: https://git-scm.com/download/mac
[dotnet]: https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer
