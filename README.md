# UltraPermissions Database

Ultra Permissions: https://www.spigotmc.org/resources/ultra-permissions.42678/

This is the huge Permission Database created by the Ultra Permissions community that allows Ultra Permissions to suggest permissions based on installed plugins.

## Format

Every line represents a Permission.

``(PluginName)+(Permission)+(Description)``

Optionally you can also add Commands like this:

``(PluginName)+(Permission)+(Description)+`(Commands seperated with ,``

### Example

``Essentials:essentials.fly+Allows the player to fly``

And with a command included:

``Essentials:essentials.fly+Allows the player to fly+/fly``

## Deploying

This file will be automatically downloaded from this repository on each restart.
