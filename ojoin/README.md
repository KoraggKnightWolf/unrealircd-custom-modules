### OJOIN ###

Forked from https://github.com/ValwareIRC/valware-unrealircd-mods/tree/main/ojoin

Changes made: Allowing opers with the ojoin privilege to set the mode on themselves via (sa)mode

Inspired by InspIRCd's module of the same name

Provides PrefixMode `+Y` which uses prefix `!`.

## Syntax
`OJOIN <chan>`

Example:

`OJOIN #unrealircd`


## Information
The user must have oper, and have the `ojoin` permission in their oper block.
You can unset the mode from yourself in a channel, but you cannot set it on yourself.
You must use `/OJOIN` if you want to have it in the channel.
