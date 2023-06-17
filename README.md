# beta-mappings
A set of deobfuscated names for Minecraft Beta 1.7.3's game code.

## Contributing
Please use [Fabric](https://github.com/FabricMC/Enigma) or [Quilt](https://github.com/QuiltMC/enigma) Enigma to contribute.
Copy and pasting names from projects like MCP is not allowed.

## Naming Conventions
- American English is always used for names.
- If there are multiple common spellings of a word, check to see if one is already used in the mappings.
- Use `PascalCase` for class names, `camelCase` for methods, fields, and arguments. Use `SCREAMING_SNAKE_CASE` for static and final fields.
- Do not use arbitrary prefixes such as `I` or `Enum` for naming classes.
- Names should be in logical order, for example, use `ObsidianBlock` instead of `BlockObsidian`.
- Names should be concise and should not contain any redundant words.
- Try to avoid uncommon abbreviations, and stick to abbreviating terms like "id", "nbt", "min"/"max", etc.
- Use plural forms of words rather than adding a "list" or "array" suffix. (e.g. `players` instead of `playerList`)
- Abbreviations should always be capitalized. (e.g. `writeToNBT` instead of `writeToNbt`)
- Method names should usually be verbs, or starting with a prefix like `get`, `set`, `is`, `has`, `can`, or `should`.
- Names such as "inventory slot" and "item stack" should not be shortened to "slot" to "item".
- Boolean fields should always start with a prefix such as the above.
- Use overload methods whenever it makes sense.
- Use "newer" terminology for things, e.g. "world" instead of level, and "block" instead of tile.
- Place classes in packages that make sense and don't nest too many packages together.
- Ensure client and server mappings are mergeable. (use similar names, place shared classes in similar packages)
- Write Javadocs for anything that could be confusing or to clear things up about the codebase.
- If you are not sure what to name something, try to be consistent with the rest of the codebase and follow general Java conventions when possible.

If you see any name not following this convention, please open an issue.
