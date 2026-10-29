# My discord theme
Only tested on Windows and Web
Meant to be used with the custom title bar enabled. If disabled there will be an unnecessary gap in the titlebar where the window buttons were supposed to be. If you want to use the Windows titlebar you can remove this block which will set it to 1 like on web.
```
:root.platform-win
{
    --titlebar-buttons-count: 4;
}
```
