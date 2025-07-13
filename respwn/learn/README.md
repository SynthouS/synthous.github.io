# reSPWN

**Welcome to the reSPWN language documentation!**

Just in case you have just stumbled upon this website, and have no idea what _SPWN_ is, here's a brief introduction for you:
**SPWN is a programming language that compiles to Geometry Dash levels.** What that means is that you can create levels by using not only the visual representation in the GD-editor, but using a "verbal" and _abstracted_ representation as well. This is especially useful for using GD triggers, which (if you want to make complicated stuff) are not really suited for the graphical workflow of the in-game editor.

If you have not worked with a programming language before, this might be a bit difficult to get into. However, you don't need much programming knowledge to get some basic things done using SPWN.

BUT, now we have a reSPWN - Community continuation of SPWN Language.

[First off, you can click here to download the latest release of reSPWN.](https://github.com/SynthouS/reSPWN/releases)

## Practical

First off, let's get to know the basic workflow of using reSPWN.
SPWN is designed so that you can work in the editor and in reSPWN at the same time, using the editor for its strengths, and reSPWN for its.

> To "compile" your reSPWN program, you use the command `respwn build [file]`, where `[file]` is the path to your reSPWN script.
> This command will do the following:
>
> - Read your levels contents
> - Compile your reSPWN program to Geometry Dash objects, making sure to not have them interfere with the things that are already in your level.
> - Append the new objects onto your level

To be clear, you do NOT have to delete and remake your level when running `respwn build` on it, it will automatically remove any old SPWN objects from the level before writing new ones. `respwn build` will by default run on the level _at the top of your levels list_. If you want it to run on a specific level, you can use the flag `--level-name [name in quotation marks]`. For example: `respwn build script.spwn --level-name "my level"`

> **Note:** The standard file ending for SPWN (and reSPWN) scripts is `.spwn`

> **Note:** SPWN (and reSPWN) generates triggers near the top of your level, so you might not see any difference.

The first part of this documentation is an introduction to the features of SPWN (and reSPWN), divided into courses. Read the [Trigger Language](triggerlanguage/trigger_language.md) course to get started!
