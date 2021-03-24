# vanilla-plus
Interface and WTF folders to sync Vanilla+ installations.

Symlink the Account folder to `[World of Warcraft Classic Install Directory]/WTF/Account` and the Interface folder to `[World of Warcraft Classic Install Directory]/Interface`.  You will need to delete the `Account` and `Interface` folders beforehand.

For example, if this repository was cloned into `D:\VanillaPlusInterface` and the Vanilla Plus installation was in `D:\Vanilla Plus`, you would run these two commands on Windows 10: <br>
`mklink /J "D:\Vanilla Plus\Interface" "D:\VanillaPlusInterface\Interface"`<br>
`mklink /J "D:\Vanilla Plus\WTF\Account" "D:\VanillaPlusInterface\Account"`<br>