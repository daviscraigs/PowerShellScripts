# Sea Battle game in PowerShell

Create 5 submarines (single-funnel) and play against computer.

![startbattle](Start-SeaBattle.gif)

## Parameter

-EnableCheats
Optional parameter. It will show computer's ships in a different table.

## Examples

Starts Sea Battle game

```powershell
.\Start-SeaBattle.ps1
```

Starts Sea Battle game in a cheat mode (shows computer's ships)

```powershell
.\Start-SeaBattle.ps1 -EnableCheats
```