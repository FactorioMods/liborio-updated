# Factorio 2.1 compatibility

Original prototype names and gameplay state are retained. The public mod uses its own namespace and imports the original state through native Factorio migrates_from ownership migration before legacy initialization can reset it. Test artifacts and raw player data are private.

Native Factorio 2.1.24 loaded the complete historical mod set, migrated its map and ran 600 simulation ticks. This is a headless result; it does not demonstrate a connected-client join or rendering.

The authentic ModMash history is retained, with a separate extraction commit for Liborio. The latest upstream recipe-checking improvements are retained. The port handles current LuaObject userdata, current cardinal directions, fluid prototypes and default 64px icons.
