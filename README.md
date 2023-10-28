# Kiwi's Nice Rice (macOS Edition)
![](https://i.ibb.co/r3NfGXm/Untitled-22.png)

A simple custom setup that I have for my macOS Terminal, themed around my anime waifu, Hasuki Komai, from Boarding School Juliet.



## Prerequisites
* Existing Homebrew installation
* icalBuddy
  
**Installation:**

```zsh
brew install ical-buddy
```
* osx-cpu-temp
  
**Installation:**

```zsh
brew install osx-cpu-temp
```

* smartmontools

**Installation:**

```zsh
brew install smartmontools
```

* Already cloned mac-motd from [here](https://github.com/douz/mac-motd)
* Existing install of [Iosevka](https://github.com/be5invis/Iosevka) Bold Extended font.


## Installation:
1. Replace the `motd.sh` file from the repo you cloned from douz, with the version from my repo.
2. Double click the `.terminal` file from my repo upon downloading
3. Inside of the Terminal window that opens, hit `Shell > Use as default`
4. In case the wallpaper doesn't show up, navigate to your locally downloaded copy of the PNG file in this repo
5. Add the following lines to the end of your `.zshrc` file, by means of `nano`:
```zsh
echo "It is currently $(date '+%A, %B %d, %Y, %T') Touwa Standard Time."
/full/path/to/repo/mac-motd/motd.sh
```
where the second line above is the actual path to your `motd.sh` file, as opposed to the placeholder in the code above.
As an example, here's what I have in those lines:
```zsh
echo "It is currently $(date '+%A, %B %d, %Y, %T') Touwa Standard Time."
/Users/pekoxusagikiwi/Downloads/mac-motd/motd.sh
```
6. Run nano again, and add the contents from the motd file in this repo to your motd file. Alternatively:
```zsh
sudo rm /etc/motd
sudo chmod +rwx /path/to/this/repo/motd
sudo cp /path/to/this/repo/motd /etc/motd
```
7. Restart your Terminal shell.

## Screenshots
![](https://i.ibb.co/r3NfGXm/Untitled-22.png)
![](https://i.ibb.co/Gn6FQgh/Untitled-24.png)
![](https://i.ibb.co/xMBGp13/Untitled-26.png)
![](https://i.ibb.co/m6kFV7q/Untitled-32.png)
![](https://i.ibb.co/FX3mn7W/Untitled-34.png)

## Disclaimer
The Terminal theme is built around a theme called Unikitty, modified by myself. I do not take credit for the original Unikitty theme. The Hasuki Komai fanart is also originally from Pixiv, though I cannot yet find the artist (I shall give attribution when I find them). The PNG has been modified to have a glassy look, as well as upscaled by yours truly, via [waifu2x](https://waifu2x.udp.jp) and [GIMP](https://www.gimp.org). Hasuki Komai, Juliet Persia, Boarding School Juliet, the nation of Touwa, the Principality of West, and all other related characters and places, are registered trademarks of Yousuke Kaneda, Kodansha USA, Liden Films, and associated parties. I do not stake any claim to any of the characters, places or other trademarks, implicit or explicit.












