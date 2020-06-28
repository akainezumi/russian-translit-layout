# Russian translit

## Description 
The goal of this keyboard layout is to reproduce the behaviour of the website **translit.ru**, but within the system and without the use of third-party plugins.

While in standard Russian layout, pressing the keys "**privet**" will produce "**зкшмуе**" which doesn't mean anything.

Using this layout, you will be able to type "**privet**" on your keyboard and obtain "**привет**".
Several combinations are possible, such as **ja** for **я**, **sh** for **ш**, **shh** for **щ**, and more, available on the website.

## How to install
Simply copy the file to ```/Library/Keyboard\ Layouts/``` and reboot. The layout will be available in the "Others" section when adding a new input source.

You can also copy the following commands :
```
git clone https://github.com/akainezumi/russian-translit-layout/ && \
cd russian-translit-layout && \
sudo cp ./russianTranslit.keylayout /Library/Keyboard \Layouts && \
sudo reboot
```
**This reboots your computer after you enter your password, be sure to save your work !**
