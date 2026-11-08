# GPT's Presidential Towers 2.0.1

Native editable asset source by **X_Bean_X** for Cities: Skylines II.

[Public Paradox release](https://mods.paradoxplaza.com/mods/164364/Any).

- `NativeDefinitions-2.0.1.zip` contains all 1,280 native payload files from the exact verified public package, including geometry, prefab definitions, materials, localization and identities.
- `native-payload-manifest.json` records the payload hashes and the public package fingerprint.
- `native-regeneration.json` records the current roof-light and Postal architecture.

This version has 32 native warm-red roof warning lights and one optional native Postal upgrade per campus. Restaurant and Grocery upgrade choices are retired. No companion runtime mod is required.

The roof fixtures use `m_ParentMesh = 0` to retain their authored roof elevation. `-1` marks them as ground-attached and is incorrect for these fixtures. Preserve existing asset identities when editing.

Historical Blender authoring archives remain at the repository root. They do not replace these current native serialized definitions or establish a one-command rebuild. Editing/import/export still requires the appropriate CS2 authoring workflow. Game assemblies, decompiled game code, private test saves and credentials are excluded.

No additional reuse license is granted by this source publication. Footprint inputs derived from OpenStreetMap remain copyright OpenStreetMap contributors and subject to ODbL 1.0: https://www.openstreetmap.org/copyright
