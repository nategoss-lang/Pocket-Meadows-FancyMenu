# Pocket Meadows Server Resource Pack

The combined server resource pack is distributed as a GitHub Release asset named:

`PocketMeadows_Server_Resources.zip`

## Permanent download URL

```
https://github.com/nategoss-lang/Pocket-Meadows-FancyMenu/releases/latest/download/PocketMeadows_Server_Resources.zip
```

## Current SHA-1

```
66254cc1456aa98c1dc9c45e655990a6131ac0ce
```

## server.properties

```properties
resource-pack=https://github.com/nategoss-lang/Pocket-Meadows-FancyMenu/releases/latest/download/PocketMeadows_Server_Resources.zip
resource-pack-sha1=66254cc1456aa98c1dc9c45e655990a6131ac0ce
require-resource-pack=true
resource-pack-prompt={"text":"","extra":[{"text":"Pocket Meadows uses a custom resource pack!","color":"gold","bold":true},{"text":"\\nPlease accept it for Pokémon models, cosmetics, music, and server visuals.","color":"yellow"}]}
```

## Updating the pack

1. Keep the asset filename exactly `PocketMeadows_Server_Resources.zip`.
2. Create a new GitHub Release.
3. Upload the new ZIP with that filename.
4. Calculate the new SHA-1.
5. Update only `resource-pack-sha1` in `server.properties`.
6. Restart the Minecraft server.

The `releases/latest/download` URL remains unchanged.

## Notes

- Rayquaza fix: removed the orphaned MoreCosmetics Astral Rayquaza model and textures from the combined server pack to prevent the T-pose/bind-pose issue.
