# postinstall

##Config

Create files `*.pkgs` and `*.aurs`

###File format 
 * first line : 

    `#label`
    
 * option, locales : 

    `#fr:label`
    `#de:label`
    
 * option, query or direct install:

    `#forced`
    
 * package list

---
>one exemple:

    #add video ?
    #fr:Ajouter les logiciels vidéo ?
    vlc mpv
    
###Usage
One file by question and one file "forced"

###Aur
files .aurs
pacman install these packages with `-U`

##Scripts
if file script.sh exist, this file is executed 

##Run
postinstall run with zenity, kdialog or console mode : `-z` `-k` `-c`(default)

You can use .desktop, 2 model exist
