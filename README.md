# Maps
The maps and active rotation used on the Minehut [Warzone](https://warz.one) server.

## Updating the Repo
When adding or modifing any map in this repo, please note some of the requirements we have for our maps.

**Updated World**

When adding a map, please make sure the world is updated and compatible with the latest version of Minecraft.
- You can figure out what version the world is by loading it into your Single Player Menu
![WorldVersion](https://i.imgur.com/7Su30rA.png)
- If the world is not updated to latest version of Minecraft, you can do so by manually loading the map in a newer version of Minecraft.

**NOTE:** When updating the world version, you **cannot** skip version 1.12.2. If the world is 1.12.2 or older, please load it in a 1.12.2 Minecraft client first, before loading it in the latest Minecraft version.

**Pruned Map**

The map needs to be pruned for it to be accepted into the repo. 
- This means that **all** chunks excluding the map itself should be deleted from the world.
- You can do this by using a program such as [MCASelector](https://github.com/Querz/mcaselector) to select and delete all the chunks that aren't apart of the map.
- After pruning the map, please make sure that you **only** include the required world files (`level.dat`, `map.json`, `region/*`).

**NOTE:** When using MCASelector, please make sure you select the region folder to open the world, not the whole folder.

**Additional Requirements:**
- You must include a valid `map.json` file (This file is used to define the coordinates and teams for the plugin).
- Ensure the map you are adding has a **commercial license**, meaning we have full permission to add the map and use it on our server.
- In the JSON, you must include **all** builders that have helped build the map a significant amount.
	- Make sure the usernames you include in the ``authors`` section of the JSON has the builder's current username.

## Tips
If you need any additional support with writing a map.json or anything else, you can try checking out our [docs](https://docs.warz.one) or by contacting a *Map Developer* on our Discord server located [here](https://warz.one/discord).
