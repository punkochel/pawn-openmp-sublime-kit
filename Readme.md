[![GitHub Release](https://img.shields.io/github/v/release/punkochel/pawn-openmp-sublime-kit.svg)](https://github.com/punkochel/pawn-openmp-sublime-kit/releases/latest)
# Pawn Kit for Sublime Text
This plugin is a fork of [Pawn syntax](https://github.com/Southclaws/pawn-sublime-language), visiting the parent page will give you more details on the plugin's capabilities.  
If you development for SA:MP, use Pawn syntax.

## Description
The plugin is adapted for development under [Open MP](https://www.open.mp/)  
Refactored snippets and completions

## Supported Libraries
-	[sscanf2](https://github.com/Y-Less/sscanf)
-	[foreach](https://github.com/Open-GTO/foreach)
-	[Pawn.CMD](https://github.com/katursis/Pawn.CMD)
-	[Pawn.Regex](https://github.com/katursis/Pawn.Regex)
-	[streamer](https://github.com/samp-incognito/samp-streamer-plugin)
-	[mdialog](https://github.com/Open-GTO/mdialog)
-	[a_mysql v40+](https://github.com/pBlueG/SA-MP-MySQL)
-	[samp-bcrypt](https://github.com/Sreyas-Sreelal/samp-bcrypt)

## Compilation on F5 key
Create a Default.sublime-keymap file in your Packages/User/ directory, then put the following code in it:
```
[
    { "keys": ["f5"], "command": "build", "context" : [{"key": "selector", "operator": "equal", "operand": "source.pawn", "match_all": true}] },
    { "keys": ["pause"], "command": "exec", "args": {"kill": true}, "context" : [{"key": "selector", "operator": "equal", "operand": "source.pawn", "match_all": true}] }
]
```

## Install
Package Control

