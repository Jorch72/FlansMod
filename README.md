FLANS MOD for MC 1.3.2

This is the official port of Flan's Mod to 1.3.2

INFORMATION TO HELPERS

If possible with the new Forge Event system, it would be preferable to remove PlayerAPI dependecy, noting that hooks will be needed for spawning, attacking, killing and dropping items etc. for when Teams mod is added. (The data file associated with the player need not be there, as long as it is somehow stored per player)
I would also like to phase out TMT and switch to NMT (Nitro Model Thingy)
If possible, a proxy class ModelRendererTurbo extends ModelRendererNitro (or whatever its called) could be made so that old content pack models do not need recompiling.


INSTALLATION

Drop new source code into fresh MCP, everything is included.