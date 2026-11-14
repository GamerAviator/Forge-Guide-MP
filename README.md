# Mighty Party Forge Guide — iPhone Duo Edition

Compact upper-screen-friendly Forge guide. Keep Mighty Party open on your lower Duo screen while tracking the quest above.

## Features

- All 54 Steel Pass upgrades and the repeating 10-step Soul Loop, using the original strategy screenshots.
- **Make → What next:** current task, ready/missing counts, recommended collection or merge action.
- **Make → Inventory:** resource requirements for 1–10 cycles, finished-item inventory, and completion checks.
- **Make → Recipes:** editable 2-to-1 merge chains and custom ingredient tiers.
- **Log merge:** deduct two components and add one crafted item.
- Completing a Soul Loop step updates the remaining requirements and uses the available inventory you logged.
- Self-contained `index.html` with all images and scripts embedded; can also be used as a standalone offline file.
- Progress saves in the browser, but does not sync between different browsers or devices.

## Multiple game accounts

Tap the purple **account selector** in the top bar. Add a separate profile for each Mighty Party account, then switch between them without mixing inventories, completed steps, Soul Loop cycles, or custom recipes. The account list summarizes the outstanding finished items per profile. You can rename or delete profiles, and **Backup all** / **Restore backup** exports and imports all profiles as one JSON file.

The first launch of this version automatically imports existing single-account Forge progress as **Main**. Account data is stored in the current browser's local storage. **It does not automatically sync between Safari, Chrome, different devices, or separate browser profiles.** Export a backup before resetting browser data, or to move accounts to another browser.

The header and browser icon use the purple Forge-inspired emblem.

## Shop Advisor and verified tiers

The **Shop Advisor** records two real shop screenshots (Latest / Previous) including each pictured item, its price, currency and purchase limit. Purchase logs and shop selection are saved separately for each game account. It estimates unmet resources and crafting merges for the remaining 10-step Soul Loop, and shows how many of a lower tier would be needed to make a finished-tier item.

The user-supplied in-game info panels confirm these chain orders:
- **Lumber:** seven tier images; tier 6 planks are the cycle resource; tiers 1–5 feed into it, tier 7 is a generator-style item.
- **Cabin:** four tiers, with the red barn as tier 4.
- **Broken Hourglass:** six tiers, from tier 1 sand through tier 5 hourglass, with tier 6 a generator-style item.

Chain item names such as `Lumber T4` and `Cabin T2` are descriptive tier labels, not guaranteed official game item names. Recipe quantities use the Forge two-identical-items-to-one-next-tier rule. An older app default that merged sand directly into the final hourglass is corrected automatically unless the user customized it. Custom recipes and previously logged inventories are preserved.

Gem and energy prices are **not interchangeable**. The displayed cost per finished-tier equivalent assumes repeated merges and excludes shop quantity limits, generator costs, cooldowns and other crafting inputs. This is an indicator of resource efficiency, not a guarantee to buy an item.

## Other merge recipes

Jewelry and transport chains are retained as **editable suggestions** until their item info panels are confirmed. The 54 Steel Pass stages are image-based and do not yet provide machine-readable quest requirements for Shop Advisor scoring.

## Enable GitHub Pages

Open repository **Settings → Pages**. Under *Build and deployment*, choose *Deploy from a branch*, select `main` and `/(root)`, then save.

Expected address after Pages publishes: https://gameraviator.github.io/Forge-Guide-MP/

## Source

- Original user-provided Forge Steel Pass and Soul Loop guide screenshots
- Official Mighty Party Forge instructions: https://byaliens.helpshift.com/hc/en/5-mighty-party/faq/89-the-forge/
