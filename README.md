<h1>fun arch linux terminal tool for ascii & figlet!</h1>
<h2>make sure you have figlet & others downloaded!!!!</h2>

### the noted dependencies below are needed

<h1>You need to do these commands once you download the files into your directory!</h1>

```
sudo pacman -S figlet
```
```
pip install python-pyfiglet

``` 

<h2>OR</h2>

<h1> v manual install  v </h1>

``` git clone https://aur.archlinux.org/nite.git ```
``` cd nite ```
``` makepkg -si ```




<h1>commands inside of nite</h1>


``` nite --help ``` (to list all commands and what they do inside of terminal)

---------------------------------------------------------------------------------------

``` nite --figlet (word) ``` create a figlet of any word


``` nite --ascii (file dir) ``` generate ascii image in your terminal


``` nite --rainbow (word) ``` create a rainbow figlet of any word


``` nite --figlet-font (font) (word) ``` create a figlet with a font from the list


``` nite --figlet-list-fonts ``` list figlet fonts

