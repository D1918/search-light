<br/>
<p align="center">
  <h3 align="center">Search Light</h3>

  <p align="center">
    A GNOME Shell 42+ Extension
    <br/>
    <br/>
  </p>
</p>

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/d1918)

![Contributors](https://img.shields.io/github/contributors/d1918/search-light?color=dark-green) ![Forks](https://img.shields.io/github/forks/d1918/search-light?style=social) ![Stargazers](https://img.shields.io/github/stars/d1918/search-light?style=social) ![Issues](https://img.shields.io/github/issues/d1918/search-light) ![License](https://img.shields.io/github/license/d1918/search-light) 

![First Release](https://raw.githubusercontent.com/d1918/search-light/main/screenshots/Screenshot%20from%202022-11-03%2011-53-28.png)


This is a Gnome Shell extension that takes the apps search widget out of Overview. Like the macOS spotlight, or Alfred.

### Notice

* Gnome 48 ready for testing
* Gnome 47 and prior will now be numer gnome-47 branch
* Gnome 46 port is ready for testing
* Gnome 45 port is ready for testing
* Gnome 44 and prior will be under g44 branch

### Features

* Popup search box
* Colors, background, borders customization
* Blurred background
* Multi-monitor support

## Blurred background

Blurred background feature requires **imagemagick** to be installed in the system which will generate the blurred image.

### Installation

Manual Installation: 
- Clone this repo
```bash
$ git clone https://github.com/d1918/search-light
```
- Use the `Makefile` to build and install
```bash 
$ cd search-light
$ make
```

From Gnome Extensions Repository

Visit [repository](https://extensions.gnome.org/extension/5489/search-light/)

### Keybinding

Ctrl+Cmd+Space (change at the preference page)
Cmd - your Windows logo, or the command logo on mac. Linux also calls this the 'Super' key.

### Credits

Blur-My-Shell for background blurring code.
