# enumIncludes

Enumerates all #Include files in the specified script by passing the
the full path to each included file, in turn, to the specified callback
function.


## Arguments
[scriptPath] (string): AutoHotkey script's filepath to scan

[callback] (Function): AutoHotkey script's filepath to scan

[AhkExe:=A_AhkPath] (string): Optional, if specified, must be the path to the AutoHotkey.exe to use as reference for the standard library folder location. Defaults is A_AhkPath


## Returns
(number): total number of identified #Include(s)
