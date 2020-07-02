# Russian translit

## Description 
The goal of this keyboard layout is to reproduce the behaviour of the website **translit.ru**, but within the system and without the use of third-party plugins, on **MacOS**.

While in standard Russian layout, pressing the keys "**privet**" will produce "**зкшмуе**" which doesn't mean anything.

Using this layout, you will be able to type "**privet**" on your keyboard and obtain "**привет**".
Several combinations are possible, such as **ja** for **я**, **sh** for **ш**, **shh** for **щ**, and more, available on the website.

## How to install

- Clone this project : ```git clone https://github.com/akainezumi/russian-translit-layout.git```
- Copy the ```russianTranslit.bundle``` folder to ```/Library/Keyboard\ Layouts/```

The layout will be available in the "Russian" section when adding a new input source. If you can't see it, logout then log back in.

## Base layouts supported

As of now the base layouts supported are :
- french AZERTY

If you can't find your layout in the list, **feel free to create an issue beginning with [Request]** and I will create a new one based on your layout as soon as possible.

## Software used

The Ukelele app was used to make this layout, using the french AZERTY keyboard layout as base layout.

## Known issues
### v1.0.3
- On non standard English MacOS layouts, <kbd>Command</kbd> + <kbd>"key"</kbd> (<kbd>⌘</kbd> + <kbd>"key"</kbd>) for letters like <key>A</key> or <key>Z</key> on french layout won't work on software like Visual Studio Code who use the position (`code` : `KeyQ` and `keyW`) rather than the value that the key sends (`key`).