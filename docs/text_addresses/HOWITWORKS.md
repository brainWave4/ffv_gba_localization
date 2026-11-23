# How does Drawing Fonts Work?
To implement the mod, I need to know how the game works so that I can make the appropriate changes.

When it comes to changing font by language, there are three kinds to consider:
## Big Fonts for Dialogs
The instruction for drawing large fonts is addressed at `C1/2971`.

The source address is stored from `BCA0` to `B8`, while the destination address is stored from `BCA2` to `BA`.

For every byte of string (next is called in `C1/299A`), it is gotten from the address stored in `B8` to be checked what kind of character it is. When the byte reads `#20`, it has a special effect for the next byte. The loop ends when the byte reads `#01` or `#00`. Otherwise, draw kana.

## Small Fonts for Menu
## "Miss" in Battle