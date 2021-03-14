__**Spell Points Variant System**__

Use `!spcast "Spell Name"` to cast a spell using Spell Points instead of using Spell Slots (see the DMG p. 298 to learn more about this variant rule.) This requires a counter named "Spell Points" and the spell must be in your spellbook (or use `-i` to ignore requirements). This uses `!cast` as a base command, so it accepts any argument that `!help cast` lists as available. You may modify the points cost without changing the level of the spell by using `-p #`.

__**Adding Homebrew**__
Start by putting your spells in a tome on the Avrae Dashboard. Export that tome to JSON and copy it to a new gvar. You can remove everything except the name and level of each spell to save space if you need to. Take the address of that gvar and put it in a uvar called `brewspells`, formatted as a list (i.e. `!uvar brewspells ["01a1a2e8-6167-4bda-a513-45cfa56b26d4"]`, separating each address with a comma). You can also make a tome available to a server by creating a server variable (svar) called `brewspells`, following the same format.

Inspired by the original alias by @silverbass#2407, but don't bug them with questions about this. 
