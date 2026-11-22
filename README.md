# anti-ghost
Version: fabric 26.1.2

## What's different:
The original [project](https://github.com/TheMasterKitty/AntiGhost/tree/master) is made using
`minecraft_version` `1.21.1` with `yarn_mappings` `1.21.1+build.3`, this version is made using
`minecraft_version` `26.1.2` with `mojang_mappings`.

The change that is made, is the conversion of
`client.player.playerScreenHandler.sendContentUpdates();`
->
`client.player.inventoryMenu.broadcastChanges();`