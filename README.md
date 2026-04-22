# Sekiro Param Comparer
Program that compares `gameparam.parambnd.dcx` files between different game versions.

## Usage
You have to put `oo2core_6_win64.dll` (for Sekiro's game files) in the folder where you have this tool's exe. I didn't want to redistribute it here on GitHub, as it is a part of a proprietary system.

1. Run `SekiroParamCompare.exe`
2. Enter first patch number
3. Enter second patch number
4. Wait for a very long time (you will see any differences printed to the console)
5. The output file will be generated to Out folder when the program finishes work

## Notes
The comparison process takes a VERY long time. This is because it compares every single value in every single row in every single param type.
If you are uncertain, check `Out\log.txt` - there rows that are the same are logged (so you can see that the program is comparing, but not detecting any changes).
You can select if you want to have this log file created or not.

## Credits
- [SoulsFormatsNEXT](https://github.com/soulsmods/SoulsFormatsNEXT) by SoulsMods organization on GitHub