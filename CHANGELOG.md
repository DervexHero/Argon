# Changelog

## 0.3.1
* Removed node_modules from VSC extension

## 0.3.0
* Added releases on GitHub
* Added local website with Argon stats
* Added option to sync only code (exclude empty instances)
* Added option for VSC extension to suppress notifications
* Connecting multiple clients to one Argon server is no longer possible
* StarterPlayer no longer ports to VSC if StarterPlayerScripts and StarterCharacterScripts are empty
* Fixed extension not stopping when plugin was still sending requests (temp fix by destroying websockets, this method will change when Electron adds support for node.js 18.2.0+)
* Fixed notifications displaying twice when Argon got enabled with command
* Fixed class filtering selector color on light mode
* Fixed plugin auto run option
* Various code optimizations

## 0.2.1 - 0.2.3
* Repository and marketplace modifications

## 0.2.0
* Added whitelist system for class filtering, suggested by [@Punctuation](https://devforum.roblox.com/u/loomiquu/)
* Fixed unclickable buttons after playtest, reported by [@Arid](https://devforum.roblox.com/u/aridthedev)
* Fixed default values of VSC extension settings
* Fixed light theme and UI scaling
* Tons of other UI optimizations and fixes
* Updated some UI buttons
* Updated VSC icons

## 0.1.4
* Instances named same as parent's property no longer cause problems
* Fixed some error messages
* Added icon for .vsix files

## 0.1.3
* Now Argon will automatically run once you open .lua or .luau file
* Added more detailed error messages

## 0.1.2
* Replaced heavy GIFs with videos
* Cleaned .ignore files

## 0.1.1
* Added better documentation
* Added new icons
* Added invalid symbols detection
* Fixed ignored classes
* Fixed .source deletion behavior (recursive rmSync)
* Made StarterPlayerScripts and StarterCharacterScripts detection server sided

## 0.1.0
* Added port to Roblox feature
* Changed default root folder name to "src" for convenience
* Fixed duplicated instances bug

## 0.0.9
* Merged changes by [@Almost89](https://github.com/Almost89) in [#1](https://github.com/DervexHero/Argon/pull/1)
* Fixed issue reported by [@LawMixer](https://devforum.roblox.com/u/bulldo344), [@commitblue](https://devforum.roblox.com/u/commitblue), [@Voidage](https://devforum.roblox.com/u/voidage) which made users unable to port large places
* Added support for renamed services
* Added history service support
* Added error ids
* Added more icons
* Moved plugin source to Argon

## 0.0.8
* Fixed bug that caused not changing .source file type

## 0.0.7
* Added Argon file icon theme

## 0.0.6
* Added support for deleting, creating and moving multiple files at once
* Moving service folders e.g. Workspace no longer causes errors
* Creating .source file inside root folder no long causes errors
* Moving .source file is no longer allowed

## 0.0.5
* Fixed critcal issue
* Added changelog
## 0.0.4
* Finished porting feature
* Added VS Code extension options

## 0.0.3
* Added port to VS Code feature (not completed)

## 0.0.2
* Updated Roblox plugin UI
* Added markdown files

## 0.0.1
* Initial release