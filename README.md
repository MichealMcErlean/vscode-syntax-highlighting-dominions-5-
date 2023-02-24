# Syntax Highlighting For Dominions 5 Mods - Event Folding Fork

Gives basic syntax highlighting for mods for the game dominions 5.
## This fork addresses:
> This syntax folds on all `#new<tag>` commands, and folds to the corresponding `#end` tag.
> Event modding, however, allows the `#newdom` command.
> This causes incorrect folding.
This fork adds recognition of `#newdom` as a non-folding command.

## Features
Highlights:
- strings (text in double quotes)
- keywords (starts with #)
- numbers
- comments

## Known Issues

Does not highlight:
- version numbers
- file paths (other than just as normal strings)
- special mod text (like \[this\])
