![Argon logo and name](https://raw.githubusercontent.com/DervexHero/Argon/main/VSC%20Extension/images/LogoName.png 'Argon')

# About
Argon is a simple two-way sync plugin for Roblox and extension for Visual Studio Code allowing developers not only sync code with ease, but any other instance as well. Argon is an alternative for Rojo not its replacement!

# Links
* Roblox [plugin](https://create.roblox.com/marketplace/asset/11263738833/)
* Visual Studio Code [extension](https://marketplace.visualstudio.com/items?itemName=Dervex.argon)
* GitHub [repository](https://github.com/DervexHero/Argon)
* DevForum [topic](https://devforum.roblox.com/t/2021776)

# Features
* Two-way sync (currently only from VS Code to Roblox is supported)
* Support for renaming, changing directory and classes
* Porting in both sides with just one button
* Instance syncing with various options
* Customizable, expandable and flexible
* Self updating class database
* Integrated file icon theme
* Very simple in use
* Fast setup

# Usage
<details>
<summary>1. Setting up the project</summary>

https://user-images.githubusercontent.com/78505208/198825348-5c5c2d42-efa9-4083-9950-69388c7ccc71.mp4
</details>


<details>
<summary>2. Managing instances</summary>

https://user-images.githubusercontent.com/78505208/198825549-e2fae0da-5f3f-49a2-a72b-37506fc2c7d0.mp4
</details>


<details>
<summary>3. Managing scripts</summary>

https://user-images.githubusercontent.com/78505208/198825573-2cd90384-49c4-482c-96f6-729e397112f7.mp4
</details>


<details>
<summary>4. Syncing code</summary>

https://user-images.githubusercontent.com/78505208/198825590-6bf1425f-ce0c-47a4-b1ef-22fa8deebc81.mp4
</details>


<details>
<summary>5. Porting to Visual Studio Code</summary>

https://user-images.githubusercontent.com/78505208/198825619-5437701d-ef82-4894-a58e-663a4793dbad.mp4
</details>


<details>
<summary>6. Porting to Roblox</summary>

https://user-images.githubusercontent.com/78505208/198825627-06661154-c964-476e-af3d-674d256c097b.mp4
</details>


<details>
<summary>7. Ignoring instances and classes</summary>

https://user-images.githubusercontent.com/78505208/198825649-f064e6db-91a3-47d1-89d3-7674de206818.mp4
</details>
 

# Demo
[![Demo video](https://raw.githubusercontent.com/DervexHero/Argon/main/VSC%20Extension/images/Demo.png)](https://youtu.be/2_jgGdP_63M 'Demo')

# Changelog
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

## Previous changes can be found in [CHANGELOG.md](https://github.com/DervexHero/Argon/blob/main/CHANGELOG.md)