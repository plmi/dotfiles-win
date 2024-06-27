# Dotfiles

Create symlink for PowerShell profile file. Requires administrator permissions.
```ps1
$ mkdir "C:\Users\Michael\Documents\PowerShell\"
$ New-Item -ItemType SymbolicLink -Path $PROFILE -Target "C:\Users\Michael\dotfiles-win\Microsoft.PowerShell_profile.ps1"
```
