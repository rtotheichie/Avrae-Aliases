Reloads your weapons that need Power Cells or Slug Canisters.  Will refill to max Energy or Ion Weapons that use a Power Cell and will load one Slug Canister at a time (for now) for Kinetic weapons.

This alias needs a few things to work: First, a custom counter with a min and max value that you wish to "reload." Next, it requires that you have used the `!bag` alias and created a bag named "Consumables." Finally, you must have at least one item named "Power Cell" or "Slug Canister" in your Consumables bag (note: "Power Cells" or "Slug Canisters" will not work).

If you have all of that setup, use `!reload <weapon name>` to reload that weapon (reset that cc) and subtract one from your available Power Cells.
